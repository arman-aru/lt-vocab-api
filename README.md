# lt-vocab-api

> Public REST API for Lithuanian A1 vocabulary and lessons (powering KalbaLab) — FastAPI, SQLAlchemy 2.0, Alembic, auth and rate limiting.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

A public REST API for Lithuanian A1 vocabulary and lessons — the content behind [KalbaLab](https://kalbalab.lt) — with search, filtering, API keys and interactive OpenAPI documentation.

## Features

- Endpoints for words, topics and lessons with pagination and filtering
- Full-text search across Lithuanian and English
- API-key authentication and per-key rate limiting
- Interactive OpenAPI / Swagger documentation
- Database migrations with Alembic
- Runs locally with one `docker compose up`

## Tech stack

Python 3.12 · FastAPI · SQLAlchemy 2.0 · Alembic · PostgreSQL · pytest · Docker

## License

[MIT](LICENSE) © Arman Salek
