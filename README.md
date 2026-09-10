<p align="center">
  <img src="docs/banner.svg" alt="CI/CD Pipeline Examples banner" width="100%" />
</p>

<h1 align="center">ci-cd-pipeline-examples</h1>

<p align="center">
  <strong>EN</strong> Stage diagrams + sample CI YAML you can adapt<br/>
  <strong>PT</strong> Diagramas de stages + YAML de CI de exemplo
</p>

<p align="center">
  <a href="https://github.com/manansbdb/ci-cd-pipeline-examples/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-CI%2FCD-f97316?style=for-the-badge" alt="CI%2FCD" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| **CI/CD stage diagrams** and a sample workflow YAML to bootstrap pipelines. | **Diagramas de stages CI/CD** e um YAML de exemplo para arrancar pipelines. |
| Copy `sample-ci.yml` into `.github/workflows/` and tweak jobs. | Copia `sample-ci.yml` para `.github/workflows/` e ajusta os jobs. |

```mermaid
flowchart LR
  A["🧪 Lint"] --> B["✅ Test"]
  B --> C["📦 Build"]
  C --> D["🚀 Deploy"]
  style A fill:#ea580c,stroke:#c2410c,color:#fff
  style B fill:#2563eb,stroke:#1d4ed8,color:#fff
  style C fill:#9333ea,stroke:#6b21a8,color:#fff
  style D fill:#16a34a,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/ci-cd-pipeline-examples.git
cd ci-cd-pipeline-examples
```

### 2) Apply workflow / Aplica o workflow

```bash
mkdir -p /path/to/your-project/.github/workflows
cp sample-ci.yml /path/to/your-project/.github/workflows/ci.yml
cp pipeline-diagram.md /path/to/your-project/docs/pipeline-diagram.md
```

### Requirements / Requisitos

- `git`
- GitHub Actions (or adapt YAML to your CI)

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/ci-cd-pipeline-examples.git
mkdir -p .github/workflows
cp ci-cd-pipeline-examples/sample-ci.yml .github/workflows/ci.yml
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `sample-ci.yml` | Example CI workflow |
| `pipeline-diagram.md` | Stage diagram notes |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
ci-cd-pipeline-examples/
├── docs/banner.svg
├── sample-ci.yml
├── pipeline-diagram.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
