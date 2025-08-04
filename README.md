# ❤️ Classificação de Doença Cardíaca com Regressão Logística

Este projeto utiliza o conjunto de dados **Statlog Heart Disease** (disponível no repositório UCI) para prever se um paciente possui ou não **doença cardíaca**, com base em variáveis clínicas e demográficas.

---

## 📌 Objetivo

Construir um modelo de **classificação binária** usando **Regressão Logística** para identificar pacientes com possível doença cardíaca, auxiliando na tomada de decisões médicas e preventivas.

---

## 📂 Sobre o Conjunto de Dados

- Origem: UCI Machine Learning Repository
- Total de registros: **270**
- Atributos: **13 variáveis independentes + 1 variável-alvo**
- Dados **completos**, sem valores ausentes

### 🎯 Variável Alvo:
- `target`:  
  - **0** = paciente saudável  
  - **1** = paciente com doença cardíaca

---

## 🗂️ Dicionário de Dados (resumo)

| Variável     | Descrição                                               | Tipo         |
|--------------|----------------------------------------------------------|--------------|
| age          | Idade do paciente                                        | Numérica     |
| sex          | Sexo (1 = masculino, 0 = feminino)                       | Nominal      |
| cp           | Tipo de dor no peito (0–3)                               | Categórica   |
| trestbps     | Pressão arterial em repouso                              | Numérica     |
| chol         | Colesterol sérico (mg/dl)                                | Numérica     |
| fbs          | Açúcar no sangue em jejum > 120mg/dl (1 = sim, 0 = não) | Nominal      |
| restecg      | Resultado do eletrocardiograma em repouso (0–2)          | Categórica   |
| thalach      | Frequência cardíaca máxima alcançada                     | Numérica     |
| exang        | Angina induzida por exercício (0 = não, 1 = sim)         | Nominal      |
| oldpeak      | Depressão ST induzida por exercício                      | Numérica     |
| slope        | Inclinação do segmento ST (0 = ascendente, 1 = plano, 2 = descendente) | Categórica |
| ca           | Número de vasos principais (0–3)                         | Nominal      |
| thal         | Tipo de talassemia (1 = normal, 2 = defeito fixo, 3 = reversível) | Nominal |
| target       | Possui doença cardíaca? (0 = não, 1 = sim)               | Binária      |

---

## 🔍 Etapas do Projeto

### 1. Análise Exploratória dos Dados (EDA)
- Distribuição das variáveis
- Análise de correlação
- Relação entre variáveis e a presença de doença cardíaca

### 2. Pré-processamento
- Codificação de variáveis categóricas

### 3. Modelagem
- Construção de modelo de **Regressão Logística**
- Avaliação com métricas: **Acurácia**, **Precision**, **Recall**, **Matriz de Confusão**

### 4. Interpretação
- Identificação das variáveis mais relevantes
- Discussão dos resultados e limitações

---

## 🧰 Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📊 Resultados

- Modelo de Regressão Logística com desempenho adequado na separação entre pacientes com e sem risco.
- Visualizações claras e interpretáveis para apoio à decisão.

---

## 👩‍💻 Autora

**Sheila Liborio**  
Engenheira e analista de dados em formação, com foco em transformar dados em decisões que geram valor.  
[LinkedIn](https://www.linkedin.com/in/sheilaliborio)

---

## ⚠️ Aviso

Este projeto é educacional e não substitui avaliação médica ou diagnóstica.  
