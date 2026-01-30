# Pós IA – Fase 1 | Assistente Especialista em Automação e IA aplicada a Produtos Digitais

## 📌 Visão Geral
Este repositório contém o desenvolvimento de um assistente virtual especializado em Automação e Inteligência Artificial aplicada a Produtos Digitais, criado como parte do **Desafio Prático da Fase 1** da Pós-Graduação em **Inteligência Artificial e Automação** da Rocketseat.

O assistente foi projetado para atuar como uma fonte de conhecimento fechada, operando com foco técnico e estratégico, respeitando limites claros de escopo e governança.

O objetivo do desafio é a **criação de um assistente especializado de IA**, utilizando o **Google NotebookLM**, com base em um produto fictício ou conceitual, devidamente documentado e estruturado para servir como fonte única e confiável de conhecimento.

## 🎯 Objetivo do Projeto

Desenvolver um **Assistente Especialista em Automação e IA aplicada a Produtos Digitais**, com comunicação **formal e técnica**, capaz de:

- Atuar como autoridade máxima sobre o produto documentado;
- Responder exclusivamente com base na documentação fornecida;
- Demonstrar o uso de técnicas de **engenharia de prompt**;
- Garantir integridade, transparência e precisão nas respostas.

## 🧠 Abordagem Utilizada

O projeto foi estruturado seguindo boas práticas de **Gestão de Produtos Digitais**, **Alta Performance** e **Prompt Engineering**, aplicando no mínimo duas técnicas de engenharia de prompt, tais como:

- Zero-Shot Prompting  
- Few-Shot Prompting  

O assistente foi projetado para **não especular**, **não inferir informações externas** e **reconhecer explicitamente seus limites** quando uma pergunta estiver fora do escopo da documentação.

## 🧠 Técnicas de Prompt Engineering Utilizadas

O desenvolvimento do assistente utilizou técnicas consolidadas de Prompt Engineering com foco em previsibilidade, governança e confiabilidade das respostas:

- **Definição explícita de papel (Role Prompting)**  
  O assistente opera sob um papel claramente definido, restringindo suas respostas ao domínio de automação, inteligência artificial e produtos digitais.

- **Classificação de escopo (Prompt Routing / Guardrails)**  
  Implementação de um classificador responsável por identificar se uma solicitação está dentro ou fora do escopo permitido, recusando educadamente perguntas não relacionadas.

- **Fonte de conhecimento fechada (Closed-Book Prompting)**  
  O assistente responde exclusivamente com base nos documentos fornecidos, evitando inferências externas ou informações não documentadas.

- **Padrão de recusa controlada (Safe Refusal Pattern)**  
  Perguntas fora do escopo resultam em respostas claras, educadas e transparentes, sem tentativa de “improvisação”.

- **Uso de exemplos orientadores (Few-Shot Prompting)**  
  Exemplos explícitos foram utilizados para reforçar o comportamento esperado em cenários dentro e fora do escopo.

Essas técnicas garantem previsibilidade de comportamento, redução de alucinações e maior confiabilidade das respostas geradas.


## 📁 Estrutura do Repositório

pos-ia-fase1-assistente-especialista/
├── README.md
└── docs/
    ├── produto.md
    └── prompt-assistente.md
    └── prompt-classificacao-escopo.md

### Descrição dos arquivos

- **README.md**  
  Documento introdutório do projeto e contextualização do desafio.

- **docs/produto.md**  
  Documento do produto, utilizado como **base única de conhecimento** pelo assistente no NotebookLM.

- **docs/prompt-assistente.md**  
  Documento contendo o **prompt completo do assistente**, incluindo:
  - Definição de personalidade  
  - Diretrizes de comportamento  
  - Técnicas de engenharia de prompt aplicadas
 
- **docs/prompt-classificacao-escopo.md**  
  Prompt responsável pela classificação de escopo e governança das respostas.

## 🚀 Entrega do Desafio

O link deste repositório é utilizado como **material oficial de entrega**, conforme exigido no desafio.  
O assistente criado no Google NotebookLM foi configurado como **público**, com acesso aos documentos aqui disponibilizados.

## 🧑‍💻 Autor

**Rodrigo Moura Araújo**  
Pós-Graduação em Inteligência Artificial e Automação – Rocketseat

