---
title: "ADR-0000: Uso de MADR para Decisões Arquiteturais"
status: accepted
date: 2026-09-28
deciders:
  - Hanniel Vieira
tags:
  - adr
  - arquitetura
  - governanca
---

# ADR-0000: Uso de MADR para Decisões Arquiteturais

* **Status:** Aceito
* **Decisores:** Hanniel Vieira
* **Data:** 2026-09-28

---

## Contexto e Declaração do Problema

Projetos de software e arquiteturas distribuídas acumulam escolhas estruturais cruciais ao longo do tempo (ex: escolha de mensageria, padrões de autenticação, particionamento de banco de dados). Sem documentação centralizada e padronizada, o racional dessas decisões se perde, gerando retrabalho e discussões recorrentes.

Precisamos de um padrão enxuto, legível em Markdown, versionável via Git e compatível com ferramentas modernas de documentação (Obsidian, GitHub).

---

## Direcionadores da Decisão

* Padronização de documentação arquitetural no formato Markdown (Version-Controlled Architecture).
* Integração direta com o repositório Git público e navegação no Obsidian Vault.
* Estrutura que capture contexto, alternativas avaliadas e trade-offs assumidos.

---

## Opções Consideradas

* **Opção 1:** MADR (Markdown Architectural Decision Records)
* **Opção 2:** Modelo Nygard (original de Michael Nygard)
* **Opção 3:** Wiki / Notion corporativo sem versionamento git

---

## Resultado da Decisão

Opção escolhida: **MADR (Markdown Architectural Decision Records)**, pois oferece o melhor equilíbrio entre formalidade técnica e simplicidade, integrando-se nativamente com Obsidian, Git e pipelines de IA/RAG.

### Consequências Positivas
* Decisões ficam versionadas ao lado do código/docs.
* Template uniforme fácil de preencher e consultar.
* Permite exposição pública das decisões em repositório aberto, preservando o restante do vault de forma privada.

### Consequências Negativas
* Exige disciplina contínua para registrar e atualizar decisões à medida que o sistema evolui.
