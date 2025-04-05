
# 📞 Projeto Telemarketing – Análise e Predição de Adesão a Produtos Bancários

Este projeto tem como objetivo analisar e prever o comportamento de clientes frente a campanhas de marketing realizadas por telefone. A ideia central é desenvolver modelos que consigam antecipar se um cliente irá ou não aderir a um produto bancário, com base em dados históricos.

---

## 🧠 Sobre o Projeto

Uma empresa do setor bancário realizou diversas campanhas de marketing telefônico oferecendo seus produtos. Este projeto busca entender o perfil dos clientes que mais tendem a aceitar uma oferta e aplicar **modelos de machine learning** para ajudar na **tomada de decisão** e **aumentar a taxa de conversão**.
---

---

### Link para a aplicacao (Livre)
https://telemarketing-z7au.onrender.com/

### Instalação

* Como/aonde fazer o download do seu projeto/programa
* Quaisquer modificação necessária nos arquivos/diretórios

### Executando o projeto

* Como rodar o projeto/programa
* Passo a passo em tópicos (bullet points)
```
bloco de código para os comandos necessários
```

## Ajuda

Qualquer ponto importante de problemas ou erros comuns
```
comando para rodar se o programa tiver uma informação de ajuda
---

## 📊 Base de Dados

- **Fonte:** [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Descrição:** Conjunto de dados com registros de campanhas de marketing direto (via telefone) de uma instituição bancária portuguesa.
- **Total de registros:** Aproximadamente 45.000 clientes

### 🔎 Variável Alvo
- `y`: indica se o cliente aderiu (`yes`) ou não (`no`) à campanha.

---

## ⚙️ Etapas Realizadas

1. **Análise Exploratória de Dados (EDA)**
   - Entendimento do perfil dos clientes
   - Identificação de padrões de comportamento
   - Correlações entre variáveis e a variável alvo

2. **Pré-processamento**
   - Tratamento de valores categóricos com One-Hot Encoding
   - Normalização de variáveis numéricas
   - Divisão entre dados de treino e teste

3. **Modelagem**
   - Modelos aplicados:
     - Regressão Logística
     - KNN
     - Árvore de Decisão
     - Random Forest
     - Gradient Boosting
     - XGBoost

4. **Avaliação**
   - Acurácia
   - Matriz de Confusão
   - Curva ROC e AUC

---

## 📈 Principais Resultados

- **Melhores modelos:** Random Forest e Gradient Boosting apresentaram excelente desempenho.
- **Variáveis mais influentes:** duração do contato, número de interações, tipo de contato e sucesso em campanhas anteriores.
- **Insight de negócio:** contatos via celular e com menos tentativas tendem a ser mais eficazes.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Estrutura do Projeto


