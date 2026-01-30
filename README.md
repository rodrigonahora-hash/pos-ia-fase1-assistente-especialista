# Pós IA – Fase 1 | Assistente Especialista em Automação e IA aplicada a Produtos Digitais

## 📌 Visão Geral

Este repositório documenta o desenvolvimento de um **assistente virtual especializado em Automação e Inteligência Artificial aplicada a Produtos Digitais**, criado como entrega do **Desafio Prático da Fase 1** da Pós-Graduação em **Inteligência Artificial e Automação** da Rocketseat.

O assistente foi concebido como um **sistema de conhecimento controlado**, com escopo bem definido, comportamento previsível e governança explícita, utilizando o **Google NotebookLM** como ambiente de execução.

O foco do projeto está menos na implementação técnica de código e mais na **arquitetura de prompts**, **controle de escopo** e **confiabilidade das respostas**.

---

## 🎯 Objetivo do Projeto

Desenvolver um assistente especialista com comunicação **formal e técnica**, capaz de:

- Operar como autoridade sobre o domínio documentado;
- Responder **exclusivamente** com base na documentação fornecida;
- Demonstrar a aplicação prática de **Prompt Engineering**;
- Rejeitar solicitações fora do escopo de forma clara e controlada;
- Garantir integridade, rastreabilidade e previsibilidade de comportamento.

---

## 🧠 Abordagem Técnica

O projeto adota princípios de **Gestão de Produtos Digitais**, **Alta Performance** e **Engenharia de Prompts**, priorizando:

- Governança de respostas  
- Redução de alucinações  
- Clareza de escopo  
- Transparência nas limitações do assistente  

O assistente **não realiza inferências externas**, **não utiliza conhecimento implícito** e **não responde perguntas não documentadas**.

---

## 🧩 Técnicas de Prompt Engineering Aplicadas

O comportamento do assistente foi estruturado a partir das seguintes técnicas:

### 🔹 Definição explícita de papel (Role Prompting)
O assistente opera sob um papel técnico bem delimitado, restrito aos temas de automação, inteligência artificial e produtos digitais.

### 🔹 Classificação de escopo (Prompt Routing / Guardrails)
Um classificador dedicado avalia se a solicitação está dentro ou fora do escopo permitido, direcionando a resposta adequada ou acionando recusa controlada.

### 🔹 Fonte de conhecimento fechada (Closed-Book Prompting)
As respostas são geradas exclusivamente a partir dos documentos fornecidos no NotebookLM, sem uso de conhecimento externo.

### 🔹 Padrão de recusa controlada (Safe Refusal Pattern)
Perguntas fora do escopo resultam em respostas educadas, objetivas e transparentes, sem tentativa de improvisação.

### 🔹 Uso de exemplos orientadores (Few-Shot Prompting)
Exemplos explícitos reforçam o comportamento esperado em cenários válidos e inválidos.

Essas técnicas garantem **previsibilidade**, **redução de riscos** e **confiabilidade** das respostas.

---

## 📁 Estrutura do Repositório

pos-ia-fase1-assistente-especialista/
├── README.md
└── docs/
    ├── produto.md
    └── prompt-assistente.md
    └── prompt-classificacao-escopo.md

### 📄 Descrição dos Arquivos

- **README.md**  
  Visão geral, abordagem técnica e contextualização do desafio.

- **docs/produto.md**  
  Documento do produto, utilizado como **base única de conhecimento** pelo assistente no NotebookLM.

- **docs/prompt-assistente.md**  
  Prompt principal do assistente, incluindo:
  - Papel e personalidade
  - Diretrizes de comportamento
  - Restrições e governança

- **docs/prompt-classificacao-escopo.md**  
  Prompt responsável pela **classificação de escopo** e controle de acesso ao domínio permitido.

- **docs/prompt-avaliacao-impacto.md**  
  Prompt dedicado à **avaliação de impacto, risco e eficiência** de decisões relacionadas à automação e IA em produtos digitais.

---

## 🚀 Entrega do Desafio

Este repositório é utilizado como **material oficial de entrega**, conforme exigido no desafio.

O assistente foi configurado no **Google NotebookLM** com acesso público aos documentos aqui disponibilizados, permitindo validação do comportamento e da arquitetura proposta.

---

## 👤 Autor

**Rodrigo Moura Araújo**  
Pós-Graduação em Inteligência Artificial e Automação — Rocketseat
