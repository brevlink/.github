# Brev

**Open-source link infrastructure.** Own the link layer, self-host the stack, drive it from the CLI.

[brevl.ink](https://brevl.ink) · [brev repository](https://github.com/brevlink/brev)

## What Brev is

Brev is a self-hosted URL shortener: custom domains, click tracking, an OpenAPI-documented API, a React dashboard and a CLI — running entirely on your own infrastructure. The stack is MIT licensed, so it stays free and self-hostable.

- **Own the domain** — short links on domains you control, behind your own reverse proxy
- **Ship anywhere** — backend, database and dashboard via Docker Compose
- **Work from the CLI** — create, list, inspect and delete links without leaving the terminal
- **Track the signal** — redirects include click tracking

## Stack

PostgreSQL · FastAPI · Caddy · Astro + React dashboard · CLI

## Get started

1. Clone [brevlink/brev](https://github.com/brevlink/brev)
2. Run the Docker Compose stack on a host you control
3. Point the CLI at your server and start publishing links

Setup details and the OpenAPI reference live in the [repository README](https://github.com/brevlink/brev).

## Brev Cloud

A managed option is planned for people who want Brev without operating the server. The self-hosted MIT stack stays free either way.
