# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.
Pull Request проходит проверки. Публикация выполняется при push в `main`.

- Endpoint готовности: `GET /health`.
- Образ: `ghcr.io/chuviss/devops-ci-app`.
- Workflow: `.github/workflows/ci.yml`.
