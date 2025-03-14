# 🏠 Boston House Price Modelling

Este repositório contém um projeto de modelagem de preços de imóveis em Boston utilizando algoritmos de **Machine Learning**. O objetivo é prever o valor das casas com base em diferentes atributos, explorando técnicas de **pré-processamento de dados, análise exploratória e ajuste de modelos preditivos**.

---

## 🚀 Objetivo do Projeto

O projeto visa desenvolver modelos preditivos para estimar o preço de casas em Boston, utilizando técnicas de Machine Learning clássicas. O processo envolve:
- **Coleta e preparação dos dados**  
- **Análise exploratória (EDA)**  
- **Treinamento e otimização de modelos**  
- **Avaliação e interpretação dos resultados**  

O conjunto de dados utilizado é o clássico **Boston Housing Dataset**, amplamente usado para problemas de regressão.

---

## 📂 Estrutura do Repositório

###📦 Boston_house_price_modelling
┣ 📜 Boston_House_Price.ipynb # Notebook principal com código e análise
┣ 📜 dataset.csv # Conjunto de dados (se necessário)
┣ 📜 README.md # Documento atual explicando o projeto
┗ 📜 requirements.txt # Bibliotecas necessárias para rodar o projeto

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Linguagem:** Python  
- **Bibliotecas principais:**
  - `pandas` → Manipulação e análise de dados  
  - `numpy` → Operações matemáticas  
  - `matplotlib` e `seaborn` → Visualização de dados  
  - `scikit-learn` → Modelagem de Machine Learning  

---

## 📊 Metodologia

1️⃣ **Coleta e Preparação de Dados**  
- Importação do dataset  
- Tratamento de valores ausentes  
- Análise das variáveis e seleção de atributos relevantes  

2️⃣ **Análise Exploratória (EDA)**  
- Estatísticas descritivas  
- Correlações entre variáveis  
- Visualizações para identificação de padrões  

3️⃣ **Modelagem e Treinamento**  
- Separação dos dados em treino e teste  
- Treinamento de modelos de regressão  
- Ajuste e otimização de hiperparâmetros  

4️⃣ **Avaliação de Modelos**  
- Uso de métricas como **RMSE, MAE e R²**  
- Comparação entre diferentes algoritmos  
- Análise de overfitting e underfitting  

### 📈 Resultados e Insights
O modelo X apresentou um erro médio de XX.X usando a métrica MAE/RMSE.
O modelo Y apresentou XX% de acurácia (R²), sendo a melhor abordagem para prever os preços.
A variável mais influente para a precificação foi (variável mais relevante do dataset).
Foi identificado que (exemplo: "áreas com maior nível de criminalidade têm preços mais baixos").

### 📌 Possíveis Melhorias
Implementar Feature Engineering para melhorar a qualidade dos dados.
Explorar outros modelos preditivos, como árvores de decisão e redes neurais.
Utilizar técnicas avançadas de otimização, como GridSearchCV e RandomizedSearchCV.
Aplicar regularização para evitar overfitting.
