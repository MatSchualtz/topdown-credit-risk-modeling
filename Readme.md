
![Status](https://img.shields.io/badge/status-in%20development-blue)
![Python](https://img.shields.io/badge/python-3.12+-green)
![License](https://img.shields.io/badge/license-MIT-orange)
![Research](https://img.shields.io/badge/type-academic%20research-purple)

## 🇺🇸 EN (PORTUGUESE BELLOW)

# IFRS 9 SICR Modeling Using a Top-Down Approach and SCR.data

### Description

This repository contains the development of a Professional Master's Dissertation in Economics focused on modeling **Significant Increase in Credit Risk (SICR)** using a **Top-Down** framework applied to aggregated credit portfolio data from the Brazilian Central Bank's **SCR.data** database.

The study investigates whether aggregate deterioration indicators, combined with macroeconomic variables and time-series models, can anticipate portfolio migration towards **IFRS 9 Stage 2**.

In addition, it evaluates how different credit portfolio segments respond to macroeconomic shocks through forecasting and stress-testing exercises.

### Research Objectives

- Build homogeneous credit portfolios using aggregated SCR.data information.
- Develop aggregate deterioration metrics aligned with IFRS 9 concepts.
- Investigate the relationship between credit risk and macroeconomic variables.
- Model the temporal dynamics of portfolio deterioration.
- Produce forward-looking forecasts consistent with IFRS 9 requirements.
- Develop predictive models for SICR identification.
- Conduct scenario analysis and stress testing.

### Research Question

> To what extent can a Top-Down approach based on aggregate deterioration metrics anticipate Significant Increase in Credit Risk (SICR) events within homogeneous credit portfolios?

### Data Sources

#### SCR.data

Public database provided by the Central Bank of Brazil containing aggregated information on:

- Active Credit Portfolio
- Non-Performing Portfolio
- Problem Assets
- Credit Products
- Customer Type (Individuals and Corporates)
- Client Size
- Geographic Region
- Financial Institution Segment
- Interest Rate Indexation
- Funding Source

#### Macroeconomic Variables

Official macroeconomic indicators including:

- Selic Interest Rate
- Inflation
- GDP
- Unemployment Rate
- Confidence Indicators
- Banking Spread

### Project Structure

```text
ifrs9-sicr-topdown-scr/
│
├── docs/
├── data/
├── notebooks/
├── src/
├── models/
├── reports/
└── tests/
```

### Main Technologies

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-Learn
- XGBoost
- LightGBM
- Matplotlib
- Seaborn
- Jupyter Notebook

### Main References

- IFRS 9 – Financial Instruments (IASB)
- Giesecke (2008) – Portfolio Credit Risk: Top-Down vs. Bottom-Up Approaches
- Gross et al. (2020) – Expected Credit Loss Modeling from a Top-Down Stress Testing Perspective

### Author

**Mateus Schualtz**

Professional Master's Degree in Economics

## 🇧🇷 PTBR

# Modelagem de SICR no IFRS 9 com Abordagem Top-Down e SCR.data

### Descrição

Este repositório contém o desenvolvimento da dissertação de Mestrado Profissional em Economia, cujo objetivo é modelar a deterioração significativa do risco de crédito (*Significant Increase in Credit Risk – SICR*) utilizando uma abordagem **Top-Down** aplicada aos dados agregados do **SCR.data**, disponibilizados pelo Banco Central do Brasil.

O estudo investiga como indicadores agregados de deterioração, combinados com variáveis macroeconômicas e modelos de séries temporais, podem antecipar movimentos de migração para o **Stage 2** do IFRS 9.

Além disso, busca avaliar a sensibilidade de diferentes segmentos de crédito a choques macroeconômicos por meio de análises prospectivas e exercícios de *stress testing*.

### Objetivos

- Construir carteiras homogêneas de crédito utilizando dados agregados do SCR.data.
- Desenvolver métricas agregadas de deterioração compatíveis com os conceitos do IFRS 9.
- Investigar a relação entre risco de crédito e variáveis macroeconômicas.
- Modelar a dinâmica temporal dos indicadores de deterioração.
- Produzir projeções (*forecasting*) consistentes com a abordagem *forward-looking* exigida pelo IFRS 9.
- Desenvolver modelos preditivos para identificação de SICR.
- Realizar análises de cenários e *stress testing*.

### Questão de Pesquisa

> Em que medida uma abordagem Top-Down, fundamentada em métricas agregadas de deterioração, apresenta capacidade preditiva na antecipação de movimentos de aumento significativo do risco de crédito (SICR) em carteiras homogêneas?

### Fonte dos Dados

#### SCR.data

Base pública disponibilizada pelo Banco Central do Brasil contendo informações agregadas sobre:

- Carteira Ativa
- Carteira Inadimplida
- Ativos Problemáticos
- Modalidades de Crédito
- Tipo de Cliente (PF/PJ)
- Porte
- Unidade da Federação
- Segmento da Instituição Financeira
- Indexador
- Origem dos Recursos

#### Variáveis Macroeconômicas

O projeto utiliza indicadores macroeconômicos provenientes de fontes oficiais como Banco Central do Brasil e IBGE:

- Taxa Selic
- Inflação
- PIB
- Taxa de Desemprego
- Índices de Confiança
- Spread Bancário

### Estrutura do Projeto

```text
ifrs9-sicr-topdown-scr/
│
├── docs/
├── data/
├── notebooks/
├── src/
├── models/
├── reports/
└── tests/
```
### Principais Tecnologias

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-Learn
- XGBoost
- LightGBM
- Matplotlib
- Seaborn
- Jupyter Notebook

### Referências Principais

- IFRS 9 – Financial Instruments (IASB)
- Giesecke (2008) – Portfolio Credit Risk: Top-Down vs. Bottom-Up Approaches
- Gross et al. (2020) – Expected Credit Loss Modeling from a Top-Down Stress Testing Perspective

### Autor

**Mateus Schualtz**

Mestrado Profissional em Economia


