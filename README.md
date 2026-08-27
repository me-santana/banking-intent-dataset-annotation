# 🏦 Banking Intent Dataset — Data Annotation & Quality

## 📌 Project Overview

This project focuses on the manual annotation and organization of a text dataset containing common customer service intents in the banking domain.

Using **Label Studio**, Portuguese-language customer messages were reviewed and labeled according to their intended meaning, resulting in a structured dataset that can serve as a foundation for **NLP experiments, intent classification, and conversational AI applications**.

The project combines practical data annotation techniques with domain knowledge gained from professional experience in bilingual customer support.

## 🎯 Objective

The main objective was to transform unstructured customer messages into a structured and labeled dataset by identifying and consistently assigning the appropriate intent to each text sample.

The project demonstrates practical experience in:

* Data annotation and labeling
* Text classification
* Intent categorization
* Dataset organization
* Data quality and consistency
* Basic NLP dataset preparation

## 🧰 Tools & Technologies

* **Label Studio** — Data annotation and labeling
* **CSV** — Dataset storage and organization
* **Git & GitHub** — Version control and documentation

## 🗂️ Dataset

The dataset contains Portuguese-language customer messages representing common banking service scenarios, including:

* Account Opening
* Card Issues
* Branch Hours
* General Information

Each record contains two main fields:

| Field      | Description              |
| ---------- | ------------------------ |
| `frase`    | Customer message         |
| `intencao` | Assigned customer intent |

### Example

| Customer Message                            | Intent          |
| ------------------------------------------- | --------------- |
| Quero abrir uma conta corrente              | Account Opening |
| Meu cartão não está funcionando             | Card Issue      |
| Qual o horário de funcionamento da agência? | Branch Hours    |

## 🧠 Annotation Process

The annotation workflow was conducted using **Label Studio**.

Each customer message was reviewed individually and assigned the intent that best represented the customer's underlying request.

The process required:

* Understanding the context and meaning of each message
* Distinguishing between different customer intents
* Applying consistent labeling criteria
* Organizing the annotated records into a structured dataset
* Reviewing labels for clarity and consistency

## 📊 Data Quality Considerations

Consistency is an important aspect of manually labeled datasets, particularly when the resulting data may later be used for machine learning or NLP applications.

During the annotation process, attention was given to:

* Consistent interpretation of intent categories
* Clear and distinguishable labels
* Accurate representation of customer requests
* Structured organization of the final dataset

## 🔍 Potential Applications

The annotated dataset can serve as a starting point for:

* Intent classification experiments
* Natural Language Processing (NLP) projects
* Conversational AI prototypes
* Customer service automation studies
* Data annotation and data quality exercises

> **Note:** This project focuses on dataset creation and annotation. No machine learning model was trained as part of this project.

## 📂 Repository Structure

```text
banking-intent-dataset-annotation/
│
├── data/
│   └── frases_anotadas_banco.csv
│
├── prints/
│   ├── label-studio-projeto.png
│   ├── tela-anotacoes.png
│   └── configuracao-labels.png
│
└── README.md
```

## 🖼️ Annotation Workflow

### 📌 Project Overview

![Label Studio - Project Overview](./prints/label-studio-projeto.png)

### ✍️ Annotation Tasks

![Annotation Tasks](./prints/tela-anotacoes.png)

### 🧩 Label Configuration

![Label Configuration](./prints/configuracao-labels.png)

## 📄 Dataset Access

The annotated dataset is available in CSV format:

🔗 [frases_anotadas_banco.csv](./data/frases_anotadas_banco.csv)

## 👩‍💻 About the Project

This project was developed as part of my practical Data Science portfolio.

My background in **bilingual customer support (Portuguese/English)** provided domain knowledge of banking customer interactions, while my ongoing studies in **Data Science** allowed me to apply that knowledge to a structured data annotation workflow.

This project reflects my interest in the intersection of **Data, AI, NLP, and customer operations**.

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/me-santana)

---

## 🇧🇷 Português

### 📌 Visão Geral

Este projeto consiste na anotação manual e organização de um conjunto de dados textuais contendo intenções comuns de atendimento no setor bancário.

Utilizando o **Label Studio**, mensagens de clientes em português foram analisadas e classificadas de acordo com sua intenção, resultando em um dataset estruturado que pode servir como base para **experimentos de NLP, classificação de intenções e aplicações de IA conversacional**.

O projeto combina técnicas práticas de anotação de dados com conhecimentos de domínio adquiridos por meio da experiência profissional em atendimento bilíngue ao cliente.

### 🎯 Objetivo

O objetivo principal foi transformar mensagens não estruturadas de clientes em um conjunto de dados estruturado e rotulado, identificando e atribuindo de forma consistente a intenção correspondente a cada mensagem.

### 🧰 Ferramentas

* **Label Studio** — Anotação e rotulagem de dados
* **CSV** — Armazenamento e organização do dataset
* **Git & GitHub** — Versionamento e documentação

### 🧠 Processo de Anotação

Cada mensagem foi analisada individualmente e classificada de acordo com a intenção que melhor representava a solicitação do cliente.

O processo envolveu:

* Interpretação do contexto e significado das mensagens
* Diferenciação entre diferentes intenções
* Aplicação consistente dos critérios de classificação
* Organização dos registros em um dataset estruturado
* Revisão das categorias para garantir clareza e consistência

### 📊 Qualidade dos Dados

A consistência é um aspecto importante em datasets anotados manualmente, especialmente quando os dados podem posteriormente ser utilizados em aplicações de Machine Learning ou NLP.

Durante o processo, foram considerados aspectos como:

* Consistência na interpretação das intenções
* Clareza entre as categorias
* Representação adequada das solicitações dos clientes
* Organização estruturada do dataset final

### 🔍 Possíveis Aplicações

O dataset pode servir como ponto de partida para:

* Experimentos de classificação de intenções
* Projetos de Processamento de Linguagem Natural (NLP)
* Protótipos de IA conversacional
* Estudos de automação de atendimento
* Projetos de anotação e qualidade de dados

> **Observação:** Este projeto é focado na criação e anotação do dataset. Nenhum modelo de Machine Learning foi treinado como parte deste projeto.

### 👩‍💻 Sobre o Projeto

Este projeto foi desenvolvido como parte do meu portfólio prático em Ciência de Dados.

Minha experiência em **atendimento bilíngue (Português/Inglês)** proporcionou conhecimento de domínio sobre interações de clientes no setor bancário, enquanto minha formação em andamento em **Ciência de Dados** permitiu aplicar esse conhecimento a um fluxo estruturado de anotação de dados.

O projeto representa meu interesse na interseção entre **Dados, IA, NLP e operações de atendimento ao cliente**.
