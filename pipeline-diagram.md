# Pipeline Diagram / Diagrama de Pipeline

## English

```text
checkout → install → lint → test → build → security scan → deploy (staging) → smoke → deploy (prod)
```

Notes:
- Run lint/test on every PR.
- Deploy to production only from protected branches/tags.
- Keep secrets in the CI secret store, never in YAML.

## Português

```text
checkout → install → lint → test → build → security scan → deploy (staging) → smoke → deploy (prod)
```

Notas:
- Execute lint/test em cada PR.
- Deploy para produção apenas a partir de branches/tags protegidas.
- Guarde segredos no secret store do CI, nunca no YAML.
