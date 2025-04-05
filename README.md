
# 📞 Projeto Telemarketing – Previsão de Adesão de Clientes

Este projeto aplica técnicas de Machine Learning para prever se um cliente irá **aderir a um produto bancário** após uma campanha de telemarketing. Utilizamos dados reais do setor bancário europeu, disponíveis publicamente, para construir modelos de classificação binária.

---

## 🎯 Objetivo

O objetivo é apoiar equipes de marketing e vendas na **tomada de decisão**, identificando os clientes com maior chance de conversão durante campanhas telefônicas.

---

## 🧩 Sobre o Dataset

- Origem: [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Registros: ~45.000 interações de clientes
- Target: `y` → Cliente aderiu (`yes`) ou não (`no`) ao produto ofertado
- Features: 
  - Dados demográficos (idade, profissão, escolaridade)
  - Comportamento financeiro (empréstimos, saldo)
  - Interações com campanhas anteriores

---

## ⚙️ Pipeline do Projeto

1. **Análise Exploratória (EDA)**
   - Gráficos, distribuições e padrões de comportamento
   - Correlações e impactos no target

2. **Pré-processamento**
   - Encoding de variáveis categóricas
   - Padronização de variáveis numéricas
   - Split treino/teste

3. **Modelagem**
   - Algoritmos testados:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - KNN
     - XGBoost
     - Gradient Boosting
   - Métricas de avaliação:
     - Acurácia
     - Matriz de Confusão
     - Curva ROC e AUC

4. **Comparação e Escolha do Melhor Modelo**

---

## 📊 Resultados Principais

- Modelos em ensemble (Random Forest / Gradient Boosting) apresentaram melhor performance.
- Fatores mais relevantes para adesão:
  - Duração do contato
  - Resultado de campanhas anteriores
  - Tipo de contato (celular tem maior conversão)
- Campanhas muito insistentes (muitos contatos) tendem a reduzir a taxa de conversão.

---

## 💼 Aplicações Reais

- Otimização de listas de contato
- Redução de custos com campanhas mal direcionadas
- Aumento da conversão com segmentação inteligente
- Ferramenta de apoio à decisão para equipes comerciais

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- XGBoost
- Jupyter Notebook

---

## 📁 Estrutura do Projeto

