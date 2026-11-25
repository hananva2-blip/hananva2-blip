# Hi, I'm Hanan 👋

QA Automation Engineer with a DevOps toolset. I build test automation with Python, pytest and Playwright, and I like owning the whole path to production: CI/CD, containers, Kubernetes and infrastructure as code.

## Featured projects

### Test automation

| Project | What it shows |
|---|---|
| [**juice-shop-automation**](https://github.com/hananva2-blip/juice-shop-automation) | UI, API and security tests for OWASP Juice Shop: Playwright Page Objects, a fresh user per test, parallel runs on Chromium and Firefox, nightly CI and Jenkins pipeline, [live Allure report](https://hananva2-blip.github.io/juice-shop-automation/) |
| [**orders-backend-tests**](https://github.com/hananva2-blip/orders-backend-tests) | Backend tests for a FastAPI + PostgreSQL orders service: every API call checked in the database too, a concurrency test against overselling, OWASP API checks (BOLA, forged and expired JWT), schema tests and a Locust load test |
| [**qa-portfolio**](https://github.com/hananva2-blip/qa-portfolio) | API, UI (Playwright) and LLM tests with pytest, running in Docker on GitHub Actions with a [live Allure report](https://hananva2-blip.github.io/qa-portfolio/) |

### Systems I built and tested end to end

| Project | What it shows |
|---|---|
| [**pulse**](https://github.com/hananva2-blip/pulse) | Synthetic monitoring platform: FastAPI, NATS JetStream, Postgres, HTTP and Playwright check runners, incidents with Telegram alerts. Unit, integration and e2e tests, Kubernetes with Argo CD, canary releases, Prometheus, Grafana, Loki and Tempo, Terraform on AWS |
| [**skywatch**](https://github.com/hananva2-blip/skywatch) | Distributed app: Flask + RabbitMQ worker, pytest with mocks, GitHub Actions (lint → test → build → GitOps tag bump), Terraform on AWS, Ansible, K3s, Helm, Prometheus |

## Toolbox

- **Testing:** Python · pytest · Playwright · requests · Allure · Locust · k6 · Page Object Model
- **Data:** PostgreSQL · SQL
- **CI/CD:** GitHub Actions · Jenkins · Docker · GHCR
- **Kubernetes:** K3s · Helm · Argo CD · Prometheus · Grafana
- **Infrastructure:** Terraform (AWS) · Ansible · Linux
