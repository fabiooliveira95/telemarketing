# 📞 Projeto Telemarketing – Predição de Adesão a Produtos Bancários

Este projeto tem como objetivo analisar e prever o comportamento de clientes frente a campanhas de marketing telefônico. Usando dados reais de campanhas anteriores, foram aplicadas técnicas de Machine Learning para identificar padrões e aumentar a taxa de conversão.

---

## 📌 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Base de Dados](#base-de-dados)
- [Etapas Realizadas](#etapas-realizadas)
- [Principais Resultados](#principais-resultados)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Contato](#contato)

---

## 🧠 Sobre o Projeto

Campanhas de telemarketing podem ser dispendiosas. Este projeto visa tornar essas campanhas mais eficientes, utilizando dados históricos para prever a probabilidade de um cliente aderir a uma oferta bancária. Com isso, é possível focar os esforços nos contatos com maior chance de sucesso.

---

## 📊 Base de Dados

- **Fonte:** [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Descrição:** Dados de campanhas de marketing direto via telefone realizadas por um banco português.
- **Tamanho:** ~45.000 registros

### 🎯 Variável Alvo
- `y`: indica se o cliente aderiu (`yes`) ou não (`no`) à campanha.

---

## ⚙️ Etapas Realizadas

1. **Análise Exploratória (EDA)**
   - Estudo do perfil dos clientes
   - Detecção de padrões comportamentais
2. **Pré-processamento**
   - One-Hot Encoding para variáveis categóricas
   - Normalização de variáveis numéricas
   - Split em treino/teste
3. **Modelagem**
   - Modelos utilizados:
     - Regressão Logística
     - KNN
     - Árvore de Decisão
     - Random Forest
     - Gradient Boosting
     - XGBoost
4. **Avaliação**
   - Métricas: Acurácia, Matriz de Confusão, Curva ROC e AUC

---

## 🏆 Principais Resultados

- **Melhores modelos:** Random Forest e Gradient Boosting
- **Variáveis mais influentes:**
  - Duração da chamada
  - Número de contatos anteriores
  - Tipo de contato (telefone fixo/celular)
  - Participação em campanhas anteriores
- **Insight de negócio:** Contatos via celular com menos tentativas são mais eficazes.

---

## 💻 Tecnologias Utilizadas

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

---

## ▶️ Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/fabiooliveira95/telemarketing.git

# Acesse o diretório
cd telemarketing

# (Opcional) Crie um ambiente virtual
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook no Jupyter ou ambiente de sua preferência
