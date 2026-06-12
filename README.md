# Customer Purchase Intention Prediction

Projeto de Machine Learning desenvolvido com o objetivo de prever a intenção de compra de clientes em uma loja web, utilizando dados demográficos, histórico de compras e comportamento de navegação.

## Descrição do Projeto

O objetivo deste projeto é criar um modelo preditivo capaz de identificar clientes com maior probabilidade de realizar compras em um e-commerce. A partir da análise dos dados disponíveis, serão aplicadas etapas de exploração, pré-processamento, modelagem e avaliação de modelos de classificação.

A variável alvo do projeto é `WebPurchases`, que representa o número de compras feitas pelo cliente pelo site da empresa.

## Objetivo

Desenvolver um modelo de classificação capaz de prever a intenção de compra dos clientes, auxiliando a empresa na tomada de decisões estratégicas e no direcionamento de campanhas de marketing.

## Base de Dados

A base utilizada contém informações sobre clientes, incluindo:

- Dados demográficos, como ano de nascimento, escolaridade, estado civil e renda;
- Informações familiares, como número de crianças em casa;
- Histórico de compras em diferentes categorias de produtos;
- Frequência de compras realizadas em diferentes canais;
- Número de visitas ao site no último mês;
- Reclamações realizadas pelo cliente.

## Etapas do Projeto

### 1. Exploração e Limpeza dos Dados

Nesta etapa, os dados são carregados, analisados e tratados para identificar possíveis valores ausentes, inconsistências e padrões iniciais.

### 2. Pré-processamento

Nesta fase são realizadas as transformações necessárias para preparar os dados para os modelos de Machine Learning, incluindo:

- Análise de correlação entre as variáveis;
- Codificação de variáveis categóricas;
- Separação entre variáveis explicativas e variável alvo;
- Divisão dos dados em treino e teste;
- Padronização das variáveis numéricas.

### 3. Modelagem

São aplicados modelos de classificação para prever a intenção de compra dos clientes. O objetivo é comparar diferentes algoritmos e identificar qual apresenta melhor desempenho para o problema.

### 4. Avaliação dos Modelos

Os modelos são avaliados utilizando métricas de classificação, como:

- Acurácia;
- Precisão;
- Recall;
- F1-score;
- Matriz de confusão.

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Como Executar o Projeto

1. Clone este repositório:

```bash
git clone https://github.com/luanaoliveira/customer-purchase-intention-prediction.git
