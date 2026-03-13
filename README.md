# Personal Boilerplates Library

A personal template library for [ChristianLempa's boilerplates CLI](https://github.com/ChristianLempa/boilerplates), containing Docker Compose templates for self-hosted services.

## Templates

| Service | Description |
|---|---|
| `authentik` | Open-source Identity Provider with SSO, MFA, and OAuth2/OIDC |
| `cloudflared` | Cloudflare Tunnel client for exposing local services without open ports |
| `fresh-rss` | Self-hosted RSS feed aggregator |
| `homebox` | Home inventory and organization system |
| `lancache` | LAN caching server for game downloads |
| `mailpit` | Email testing tool with built-in SMTP server and web UI |
| `open-webui` | Web UI for Ollama and OpenAI-compatible LLM backends |
| `paperless-ngx` | Document management with OCR, tagging, and full-text search |
| `portainer` | Container management UI for Docker and Docker Swarm |
| `traefik-proxy` | Traefik v3 reverse proxy with Cloudflare DNS challenge for TLS |

## Usage

### Add this repo as a custom source

```sh
boilerplates repo add <name> <url>
```

### Generate a template

```sh
boilerplates generate compose/<service-name>
```

## Structure

Templates live under `library/compose/<service-name>/` and follow the boilerplates schema version 1.2.
