# Adult Census Income - Machine Learning Classification

## 📌 Sobre o Projeto

Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever a faixa de renda de indivíduos utilizando informações demográficas e socioeconômicas do dataset **Adult Census Income**.

O problema é tratado como uma tarefa de **classificação supervisionada**, onde o modelo busca identificar se uma pessoa possui renda:

- <=50K
- >50K

Através de variáveis como idade, escolaridade, ocupação, estado civil, horas trabalhadas e outras características.

---

# 🎯 Objetivo

Construir um pipeline completo de Machine Learning envolvendo:

- análise exploratória dos dados (EDA)
- limpeza e preparação dos dados
- tratamento de valores ausentes
- transformação de variáveis categóricas
- engenharia de atributos
- treinamento de modelos supervisionados
- avaliação de desempenho

---

# 🗂️ Dataset

Dataset utilizado:

**Adult Census Income Dataset - UCI Machine Learning Repository**

Principais variáveis:

### Numéricas
- age
- fnlwgt
- education-num
- capital-gain
- capital-loss
- hours-per-week

### Categóricas
- workclass
- education
- marital-status
- occupation
- relationship
- race
- sex
- native-country

Variável alvo:

- income

---

# 🔎 Análise Exploratória (EDA)

Foram realizadas análises para compreender:

- distribuição das variáveis
- relação entre características e renda
- identificação de padrões nos dados
- análise de variáveis importantes para o modelo

Visualizações utilizadas:

- gráficos de distribuição
- gráficos de comparação
- análise de frequência
- correlação entre variáveis numéricas

---

# ⚙️ Pré-processamento

Etapas realizadas:

- tratamento de valores ausentes
- separação entre variável preditora e variável alvo
- codificação de variáveis categóricas
- divisão dos dados em treino e teste

Divisão utilizada:

- 80% treino
- 20% teste

---

# 🤖 Modelagem

Foram aplicadas técnicas de aprendizado supervisionado para classificação.

Modelos utilizados:

- Logistic Regression
- Random Forest
- outros modelos avaliados durante o desenvolvimento

---

# 📊 Avaliação do Modelo

O desempenho foi analisado utilizando métricas de classificação:

- Accuracy
- Precision
- Recall
- F1-score

A avaliação permitiu comparar o desempenho dos modelos e identificar qual apresentou melhor capacidade preditiva.

---

# 🧠 Principais Aprendizados

Durante o desenvolvimento do projeto foram aplicados conceitos fundamentais de Machine Learning:

- importância da preparação dos dados
- impacto das variáveis categóricas no modelo
- necessidade de avaliação correta do desempenho
- interpretação dos resultados obtidos pelo algoritmo

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 📁 Estrutura do Projeto
