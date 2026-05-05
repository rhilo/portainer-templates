# portainer-templates

A curated [Portainer](https://www.portainer.io/) v3 templates file containing a hand-picked selection of open-source, self-hostable applications.

## Usage

In Portainer, go to **Settings → App Templates** and set the URL to:

```
https://raw.githubusercontent.com/rhilo/portainer-templates/main/templates.json
```

## Included templates

| # | Type | Title | Category |
|---|------|-------|----------|
| 1 | Container | Open WebUI | AI / LLM |
| 2 | Container | CoreDNS | Networking / DNS |
| 3 | Container | Traefik | Networking / Proxy |
| 4 | Container | PostgreSQL | Database |
| 5 | Container | MariaDB | Database |
| 6 | Container | MongoDB | Database |
| 7 | Container | Redis | Database / Cache |
| 8 | Container | MinIO | Storage |
| 9 | Container | Gitea | Development / Git |
| 10 | Container | Grafana | Monitoring |
| 11 | Container | Nginx | Web server |
| 12 | Container | Caddy | Web server |
| 13 | Container | Docker Registry | Docker |
| 14 | Container | File Browser | Filesystem / Storage |
| 15 | Container | Jenkins | CI/CD |
| 16 | Container | RabbitMQ | Messaging |
| 17 | Container | InfluxDB | Database / Monitoring |
| 18 | Container | Prometheus | Monitoring |
| 19 | Swarm Stack | Portainer Agent | Portainer |
| 20 | Compose Stack | WordPress | CMS |
| 21 | Compose Stack | Node-RED | Automation / IoT |

## What is excluded

- Microsoft / Windows containers (SQL Server, OMS Agent, etc.)
- Enterprise / paid / licensed software (LiveSwitch, TOSIBOX, Manubes, Softing EdgeConnector, OPC Router, Litmus Edge, etc.)
- Third-party SaaS monitoring agents that require external API keys (Datadog, Sematext)
- Industrial / OT-specific tooling (Ignition Gateway, Anyviz, FDO, OpenAMT, etc.)
