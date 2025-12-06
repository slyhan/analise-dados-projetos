# 📊 Employee Churn Analysis – Análise de Rotatividade de Funcionários

Este projeto tem como objetivo analisar os fatores que influenciam a rotatividade de funcionários (churn) em uma empresa, utilizando um dataset de Recursos Humanos e combinando Python (EDA + estatística) com um dashboard no Power BI para apresentar insights executivos.

## ⭐ Principais Entregáveis

* 🔍 Análise exploratória completa (Python)

* 🧼 Limpeza e padronização dos dados

* 📈 Visualizações de distribuição e correlação

* 🧠 Identificação de grupos de risco

* 📊 Dashboard interativo no Power BI

* 📌 KPIs executivos

* 🎯 Insights acionáveis para o time de RH

## 🧼 1. Preparação dos Dados

No notebook foram aplicados passos importantes de pré-processamento:

* Padronização dos nomes das colunas

* Verificação de valores ausentes

* Identificação de colunas numéricas e categóricas

* Tratamento de tipos incorretos

* Conversão de variáveis categóricas quando necessário

* Análise da distribuição das variáveis

## 🔍 2. Análise Exploratória (EDA)
A análise incluiu:

#### 📊 Análises Univariadas

* Distribuição de idade

* Análise de gênero

* Tempo de empresa

* Salário mensal

* Anos desde a última promoção

* Satisfação no trabalho

#### 🔗 Análises Bivariadas

* Relação entre Salário x Churn

* Relação entre Tempo de empresa x Churn

* Relação entre Satisfação x Churn

* Comparação entre níveis de cargo

* Comparação entre departamentos

#### Gráficos como:

* Countplots

* Distribuições com histograma

* Boxplots

* Barras agrupadas

## 🧩 3. Fatores Críticos Identificados

Durante a análise foram observados padrões importantes:

* Funcionários com menor tempo de empresa apresentaram maior churn

* Colaboradores com salário menor saem com mais frequência

* A faixa etária 26–35 concentra grande parte das saídas

* Rotatividade aumenta quando há muitos anos desde a última promoção

* Alguns gestores possuem maior taxa de desligamentos

* Departamentos como Sales e R&D têm risco diferente

## 📊 4. Dashboard no Power BI

O dashboard apresenta:

#### 📌 KPIs Executivos

* Taxa de Rotatividade: 16,12%

* Taxa de Rotatividade – Grupo de Risco: 24,67%

* Total de Funcionários: 1470

* Total de Desligados: 237

#### 📈 Visualizações

* Rotatividade por tempo de empresa do gestor

* Rotatividade por anos desde a última promoção

* Filtros por:

    * Renda Mensal

    * Departamento

    * Faixa Etária

    * Nível de Cargo

## 🛠️ Ferramentas Utilizadas
#### Python

* Pandas

* NumPy

* Matplotlib

* Seaborn

#### Power BI

* Card KPIs

* Gráficos de barras

* Filtros e segmentações

* Modelagem simples