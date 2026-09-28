# Software Architecture & System Design

> Guia prático, decisões arquiteturais (ADRs) e padrões de System Design para sistemas escaláveis, distribuídos e resilientes.

**Autor:** Hanniel Vieira  
**Padrão de Decisões:** [MADR (Markdown Architectural Decision Records)](https://adr.github.io/madr/)

---

## Estrutura do Repositório

```text
software-architecture/
├── adrs/                   # Architectural Decision Records (Decisões de Design)
│   ├── template.md         # Template oficial MADR para novas decisões
│   └── 0000-*.md           # Registros de decisões numerados
├── system-design/          # Padrões e Fundamentos de System Design
│   ├── patterns/           # Padrões arquiteturais (CQRS, Event-Driven, Saga, etc.)
│   └── trade-offs/         # Análises comparativas (SQL vs NoSQL, Kafka vs RabbitMQ, etc.)
└── README.md
```

---

## Architectural Decision Records (ADRs)

| ADR | Título | Status | Data |
| :--- | :--- | :--- | :--- |
| [ADR-0000](adrs/0000-uso-de-madr-para-decisoes-arquiteturais.md) | Uso de MADR para Decisões Arquiteturais | Aceito | 2026-09-28 |

### Como criar um novo ADR:
1. Copie o arquivo [`adrs/template.md`](adrs/template.md) para `adrs/NNNN-titulo-da-decisao.md`.
2. Documente o contexto, direcionadores, alternativas avaliadas e os trade-offs assumidos.
3. Adicione o novo registro na tabela acima.

---

## Tópicos de System Design em Foco

* **Mensageria e Streaming:** RabbitMQ (garantia de entrega, routing) vs Apache Kafka (alta vazão, log distribuído).
* **Consistência e Transações:** ACID vs BASE, Transações Distribuídas (Saga Pattern, Outbox Pattern).
* **Armazenamento:** SQL Relacional (PostgreSQL) vs NoSQL (Documentos/Chave-Valor) vs Blob Storage (S3/MinIO).
* **Escalabilidade & Resiliência:** Layer 7 Load Balancers, API Gateways, Circuit Breaker, Rate Limiting e Cache Distribuído (Redis).
