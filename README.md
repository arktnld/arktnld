# Cleberson Gomes

**Senior Software Engineer | Backend | Data Engineering | Integrações | AI Tooling**

Engenheiro de Software Senior com 6+ anos de experiência construindo sistemas que rodam em produção. Especialista em integrações entre ERPs, CRMs e APIs de telecom, pipelines de dados e automação com IA.

Já entreguei 20+ integrações em produção para empresas de diferentes setores — telecom, educação, financeiro, varejo. Meu foco é resolver problemas reais com código que funciona, escala e não quebra.

---

## Principais Áreas de Atuação

**Integrações ERP/CRM**
- 20+ integrações em produção com ERPs e CRMs reais
- Protheus (TOTVS), Sankhya, Senior, Omie, Voalle, MKSolutions
- Pipefy, Ploomes, Kommo, Chatwoot
- APIs REST e SOAP, incluindo sistemas mal documentados e legados

**Data Engineering**
- Pipelines ETL com checkpoint/resume, retry automático e observabilidade
- Staging em DuckDB, carga em PostgreSQL, sync incremental
- Ingestão de dados de provedores de internet: IXC Provedor, Hubsoft, FVS, Hits API
- Modelagem de dados, transformação e disponibilização pra dashboards e IA

**APIs & Backend**
- REST APIs em Go e Python (FastAPI) para produção de alto volume
- WhatsApp API com protocolo nativo — 129 endpoints, multi-sessão, webhooks com retry
- API wrappers para Claude Code CLI com sessions persistentes e streaming SSE
- Plataforma de testes de API ERP com playbooks automatizados e assertions

**AI Tooling & Automação**
- Bots WhatsApp e Telegram integrados com Claude SDK
- Fork customizado do Open WebUI com Docling OCR e branding próprio
- Avaliação de modelos LLM com DeepEval (25+ métricas)
- Orquestração de workflows com n8n em produção
- Deploy de LLMs em Kubernetes (Ollama + Open WebUI)

**Infra & DevOps**
- Docker, Kubernetes, Linux (Arch)
- Deploy e operação de serviços em VPS e cloud (AWS)
- CI/CD, monitoramento e manutenção de ambientes produtivos

---

## Projetos em Destaque

### [wago-api](https://github.com/arktnld/wago-api) — WhatsApp REST API
API Go com protocolo nativo WhatsApp. 129 endpoints, multi-sessão, Docker image de 44MB. Webhooks com retry, rate limiting, proteção SSRF. Drop-in replacement do wwebjs-api.

### [claude-code-api](https://github.com/arktnld/claude-code-api) — Claude Code como serviço
REST API que expõe o Claude Code CLI via FastAPI. Sessions persistentes, streaming SSE, jobs assíncronos com webhooks. Usa o plano Max/Pro existente — sem custo extra de API.

### [tap-ixc](https://github.com/arktnld/tap-ixc) — ETL para provedores de internet
Pipeline Python que sincroniza dados da API IXC Provedor para PostgreSQL. Checkpoint por stage, retry automático, observabilidade nativa. Usado em produção por provedores de internet.

### [erp-api-tester-next](https://github.com/arktnld/erp-api-tester-next) — Plataforma de testes de API ERP
App Next.js/TypeScript para testar integrações com ERPs. Playbooks automatizados, assertions, reports compartilhados, RBAC com Clerk. Monorepo com Prisma e PostgreSQL.

### [cbt-llm-kit](https://github.com/arktnld/cbt-llm-kit) — Terapia cognitiva guiada por IA
Toolkit de TCC (Terapia Cognitivo-Comportamental) para assistentes de IA. Fluxo estruturado de 12 passos, check-ins diários, análise de padrões. Funciona com Claude, Gemini, Cursor e mais.

### [claude-code-whatsapp](https://github.com/arktnld/claude-code-whatsapp) — Acesso remoto ao Claude Code via WhatsApp
Bot Python que conecta WhatsApp ao Claude Code. Permite executar código, gerenciar arquivos e rodar comandos direto pelo celular.

---

## Tech Stack

```
Backend:      Python (FastAPI, Flask) · Go · TypeScript (Next.js)
Data:         PostgreSQL · DuckDB · ETL/ELT · Prisma
Integrações:  REST · SOAP · Webhooks · n8n
AI:           Claude SDK · Ollama · Open WebUI · DeepEval
Infra:        Docker · Kubernetes · Linux · AWS
Automação:    WhatsApp API · Telegram Bot · RPA
```

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arktnld/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/arktnld)

Disponível para projetos freelance e consultoria.
