# horse-colic-prediction
Usando de um dataset com 299 casos distintos, abordamos nesse trabalho, equinos que passaram por algum tipo de dor abdominal classificada como cólica, uma das principais causas de morte e atendimento médico veterinário. A base reúne prontuários médicos e categorias de grande importância para a determinação do desfecho do animal.

## 📊 Dataset

- Base: UCI Horse Colic Dataset (Kaggle)
- Registros: 299 instâncias
- Atributos: 28 variáveis clínicas e qualitativas
- Problema: Classificação multiclasse desbalanceada

---

## ⚙️ Pipeline do Projeto

O fluxo de desenvolvimento seguiu as etapas:

- Análise Exploratória de Dados (EDA)
- Tratamento de valores ausentes (missing values)
- Remoção e ajuste de variáveis irrelevantes
- Codificação de variáveis categóricas (One-Hot Encoding)
- Normalização e preparação dos dados
- Construção de Pipeline com Scikit-Learn
- Divisão treino/teste (75/25)
- Balanceamento de classes

---

## 🤖 Modelos Utilizados

Foram testados e comparados os seguintes algoritmos:

- Regressão Logística
- Random Forest
- Decision Tree
- Support Vector Classifier (SVC)

O melhor desempenho foi obtido com **Regressão Logística**, após ajuste de hiperparâmetros.

---

## 📈 Resultados

- Melhor acurácia: **68%**
- Métricas utilizadas:
  - Accuracy
  - Precision
  - Recall
  - F1-score

O modelo apresentou dificuldades na classe “Euthanized”, devido a fatores externos não presentes no dataset.

---

## 🧠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## 📄 Artigo Científico

O artigo completo com a fundamentação teórica, metodologia e análise dos resultados está disponível no repositório:

👉 `artigo-horse-colic.pdf`
