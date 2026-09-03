# Checkpoint 01 — Modelagem Linear para Aprendizado de Máquina

##  Sobre o projeto

Este projeto foi desenvolvido como parte do **Checkpoint 01 do 2º semestre**, na disciplina de **Modelagem Linear para Aprendizado de Máquina (MLAM)**.

O trabalho apresenta a aplicação de técnicas de **análise de dados, pré-processamento e aprendizado de máquina**, utilizando Python e bibliotecas como Pandas, NumPy, Matplotlib, Seaborn e Scikit-learn.

O notebook está dividido em três exercícios, trabalhando diferentes problemas de classificação.

---

##  Exercício 1 — Saúde

O primeiro exercício utiliza o dataset **Breast Cancer Wisconsin**, disponibilizado pelo Scikit-learn.

O objetivo é realizar a classificação de tumores, utilizando características dos dados para identificar as classes.

Neste exercício foram realizados:

- Carregamento e organização dos dados;
- Análise inicial do dataset;
- Verificação da qualidade dos dados;
- Análise estatística;
- Visualização dos dados;
- Separação entre variáveis preditoras e variável-alvo;
- Divisão dos dados em treinamento e teste;
- Pré-processamento;
- Treinamento de modelos de classificação;
- Avaliação através de acurácia e matriz de confusão.

---

##  Exercício 2 — Economia

O segundo exercício utiliza o dataset **Adult**, com o objetivo de classificar a faixa de renda dos indivíduos.

A variável-alvo foi organizada em duas classes:

- `0` → renda menor ou igual a 50 mil dólares;
- `1` → renda maior que 50 mil dólares.

Foram realizadas etapas de:

- Carregamento do dataset;
- Inspeção dos dados;
- Verificação de valores ausentes e duplicados;
- Análise exploratória;
- Separação entre `X` e `y`;
- Divisão entre treinamento e teste;
- Pré-processamento de variáveis numéricas e categóricas;
- Treinamento de modelos de classificação;
- Comparação dos resultados;
- Avaliação através de acurácia e matriz de confusão.

---

##  Exercício 3 — Telecomunicações

O terceiro exercício apresenta um desafio relacionado à área de **Telecomunicações**, utilizando o **Iranian Churn Dataset**.

O objetivo é prever o abandono de clientes, representado pela variável `Churn`.

As classes são:

- `0` → cliente que não abandonou o serviço;
- `1` → cliente que abandonou o serviço.

### Etapas realizadas

1. Carregamento do dataset;
2. Análise das dimensões e tipos dos dados;
3. Verificação de valores ausentes;
4. Identificação e tratamento de registros duplicados;
5. Verificação de valores inconsistentes;
6. Análise da distribuição das classes;
7. Criação de visualizações;
8. Separação entre variáveis preditoras (`X`) e variável-alvo (`y`);
9. Divisão dos dados em treinamento e teste;
10. Pré-processamento dos dados;
11. Treinamento de uma **Regressão Logística**;
12. Treinamento de um **Random Forest**;
13. Comparação da acurácia dos modelos;
14. Análise da matriz de confusão do melhor modelo.

---

##  Modelos utilizados

Durante o projeto foram utilizados diferentes algoritmos de classificação, incluindo:

- **Regressão Logística**
- **Árvore de Decisão**
- **Random Forest**

Os modelos foram avaliados utilizando principalmente a **acurácia** e a **matriz de confusão**.

---

## 🛠️ Tecnologias utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Estrutura do projeto

```text
Checkpoint_01_2SEM_MLAM/
│
├── Checkpoint_01_2SEM_MLAM_1CCPKJ.ipynb
├── Customer Churn.csv
├── adult.csv
└── README.md
