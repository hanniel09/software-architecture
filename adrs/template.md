---
title: "ADR-XXXX: [Título curto da decisão tomada]"
status: proposed
date: YYYY-MM-DD
deciders:
  - Hanniel Vieira
tags:
  - adr
  - arquitetura
---

# [Título curto da decisão tomada]

* **Status:** [proposto | aceito | rejeitado | depreciado | substituído por ADR-XXXX]
* **Decisores:** Hanniel Vieira
* **Data:** YYYY-MM-DD

---

## Contexto e Declaração do Problema

[Descreva em 2 a 3 parágrafos o problema que motivou esta decisão técnica. Qual restrição de negócio, escalabilidade ou manutenibilidade estamos resolvendo?]

---

## Direcionadores da Decisão (Decision Drivers)

* [Direcionador 1, ex: latência máxima de 200ms sob pico]
* [Direcionador 2, ex: facilidade de integração com microsserviços Java/Node]
* [Direcionador 3, ex: custo de infraestrutura e suporte a clustering]

---

## Opções Consideradas

* **Opção 1:** [Nome da Opção 1]
* **Opção 2:** [Nome da Opção 2]
* **Opção 3:** [Nome da Opção 3]

---

## Resultado da Decisão

Opção escolhida: **[Opção X]**, porque [justificativa técnica concisa].

### Consequências Positivas
* [Ganho 1, ex: desacoplamento temporal entre o checkout e o processamento de ingressos]
* [Ganho 2, ex: garantia de entrega via persistência em disco]

### Consequências Negativas (Trade-offs)
* [Trade-off 1, ex: complexidade adicional de monitoramento e Dead Letter Queues]
* [Trade-off 2, ex: necessidade de gerenciar consistência eventual]

---

## Comparativo das Opções

### Opção 1: [Nome]
* **Prós:** [Vantagem A, Vantagem B]
* **Contras:** [Desvantagem A, Desvantagem B]

### Opção 2: [Nome]
* **Prós:** [Vantagem A, Vantagem B]
* **Contras:** [Desvantagem A, Desvantagem B]

---

## Referências e Links
* [Link 1](https://exemplo.com)
