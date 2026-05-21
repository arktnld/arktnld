# Cleberson Gomes

**Engenheiro de Software Senior** com 6+ anos construindo sistemas backend, integrações de API e pipelines de dados em produção.

Foco em resolver problemas reais: APIs que aguentam carga, ETLs que não perdem dados, automações que funcionam sem babá.

## O que eu faço

- **APIs & Backend** — REST APIs em Go e Python (FastAPI) para produção. WhatsApp API com 129 endpoints servindo múltiplas sessões simultâneas.
- **Data Engineering** — ETL pipelines com checkpoint/resume, retry automático e observabilidade. Sync de dados entre ERPs, CRMs e bancos PostgreSQL.
- **Integrações** — Conectei sistemas como Sankhya, Protheus (TOTVS), IXC Provedor, Kommo CRM, Ploomes. Sei lidar com APIs mal documentadas.
- **AI Tooling** — Ferramentas que colocam LLMs pra trabalhar: bots WhatsApp, REST wrappers, deploy de modelos em Kubernetes.
- **Infra** — Docker, Kubernetes, Linux. Deploy e manutenção de serviços em VPS e cloud.

## Stack

```
Backend:    Python · Go · TypeScript          Infra:     Docker · Kubernetes · Linux
Frameworks: FastAPI · Next.js · Prisma        Cloud:     AWS · VPS
Dados:      PostgreSQL · DuckDB · ETL         AI:        Claude SDK · Ollama · Open WebUI
Automação:  n8n · WhatsApp API                OS:        Arch Linux · Hyprland · Neovim
```

## Projetos em destaque

### [wago-api](https://github.com/arktnld/wago-api) — WhatsApp REST API
API Go com protocolo nativo WhatsApp. 129 endpoints, multi-sessão, Docker image de 44MB. Webhooks com retry, rate limiting, proteção SSRF.

### [claude-code-api](https://github.com/arktnld/claude-code-api) — Claude Code como serviço
REST API que expõe o Claude Code CLI via FastAPI. Sessions persistentes, streaming SSE, jobs assíncronos com webhooks.

### [tap-ixc](https://github.com/arktnld/tap-ixc) — ETL para provedores de internet
Pipeline Python que sincroniza dados da API IXC Provedor para PostgreSQL. Checkpoint por stage, retry automático, observabilidade nativa.

### [erp-api-tester-next](https://github.com/arktnld/erp-api-tester-next) — Plataforma de testes de API ERP
App Next.js/TypeScript para testar integrações com ERPs. Playbooks automatizados, assertions, reports compartilhados, RBAC.

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arktnld/)

Disponível para projetos freelance e consultoria.
