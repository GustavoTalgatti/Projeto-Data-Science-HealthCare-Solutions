# Projeto de Data Science: Previsão de Readmissão Hospitalar na HealthCare Solutions

**Autor:** Luis Gustavo dos Santos Talgatti  
**Instituição:** UniFECAF

---

## 1. Visão Geral do Projeto

Este repositório contém o projeto prático da disciplina de Data Science, focado no desafio da rede de hospitais **HealthCare Solutions**. O objetivo é realizar um projeto completo de ciência de dados, desde a coleta até a modelagem, para analisar dados de pacientes e prever o risco de **readmissão hospitalar em 30 dias**.

A análise utiliza quatro fontes de dados simulados (mock data) para replicar um cenário hospitalar real:
1.  **Registros Eletrônicos de Saúde (EHR)**
2.  **Dispositivos de Monitoramento (Sinais Vitais)**
3.  **Pesquisas de Satisfação de Pacientes**
4.  **Dados Administrativos (Hospitalares)**

O notebook principal (`Trabalho_Data_Science.ipynb`) documenta toda a metodologia, desde a limpeza dos dados e análise exploratória até a criação de um modelo de machine learning interpretável.

---

## 2. Estrutura do Repositório
```
├── dados/
  │ 
  ├── administrative_data.csv
  │ 
  ├── device_monitoring.csv
  │ 
  ├── ehr_records.csv
  │ 
  └── patient_satisfaction.csv 
├── graficos/
  │ 
  ├── plot_1_target_distribution.png
  │ 
  ├── ... (outros 11 gráficos) 
  │
  └── plot_13_feature_importance_lr.png 
├── merged_healthcare_data.csv 
├── Projeto - Data Science - Luis Talgatti.pdf (Relatório Teórico) 
├── Trabalho_Data_Science.ipynb (Notebook Principal)
├── Trabalho_Data_Science.pdf (Notebook em PDF) 
└── README.md (Este arquivo)
```
---

## 3. Como Executar o Projeto

### Pré-requisitos

O projeto foi desenvolvido em Python 3.11.9. As bibliotecas essenciais estão listadas abaixo.

```
# Bibliotecas principais
os
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyterlab (ou jupyter notebook)
```
