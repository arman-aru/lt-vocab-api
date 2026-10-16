# lt-vocab-api

> Public REST API for Lithuanian A1 vocabulary and lessons (powering KalbaLab) — FastAPI, SQLAlchemy 2.0, Alembic, auth and rate limiting.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-Python-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 1 — Python & Go foundations**). I build in the open — follow the commits and the roadmap below.

## Why this project

Build a real Python backend the right way — the vocabulary behind [KalbaLab](https://kalbalab.lt) as a clean, documented public API.

## What I'm learning

- FastAPI routing, dependency injection and OpenAPI docs
- SQLAlchemy 2.0 models and Alembic migrations
- API keys / JWT auth and rate limiting
- Pagination, filtering and search
- Integration tests against a real PostgreSQL in Docker

## Planned stack

Python 3.12 · FastAPI · SQLAlchemy 2.0 · Alembic · PostgreSQL · pytest · Docker

## Roadmap

- [ ] FastAPI skeleton, settings, health check, CI
- [ ] Models + migrations for words, topics and lessons
- [ ] Seed data import (220 A1 words)
- [ ] Read endpoints with pagination, filtering and search
- [ ] API keys + rate limiting
- [ ] Integration tests with PostgreSQL in Docker
- [ ] Dockerfile + docker-compose
- [ ] Public docs page and example requests

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | **lt-vocab-api** (this repo) | Python | 1 |
| 3 | [parcel-locker-api](https://github.com/arman-aru/parcel-locker-api) | Golang | 1 |
| 4 | [go-uptime](https://github.com/arman-aru/go-uptime) | Golang | 1 |
| 5 | [ci-cd-pipelines](https://github.com/arman-aru/ci-cd-pipelines) | DevOps | 2 |
| 6 | [k8s-gitops-lab](https://github.com/arman-aru/k8s-gitops-lab) | DevOps | 2 |
| 7 | [terraform-aws-platform](https://github.com/arman-aru/terraform-aws-platform) | Cloud Computing | 3 |
| 8 | [serverless-media-pipeline](https://github.com/arman-aru/serverless-media-pipeline) | Cloud Computing | 3 |
| 9 | [site-audit-agent](https://github.com/arman-aru/site-audit-agent) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek
