# 🧠 Análise de Risco de Crédito

### 📌 Descrição
Este projeto tem como objetivo **analisar e prever o risco de crédito de clientes**, utilizando técnicas de **ciência de dados** e **aprendizado de máquina**.  
A análise busca identificar padrões que diferenciam bons e maus pagadores, auxiliando decisões de crédito em instituições financeiras ou empresas que vendem a prazo.

---

### 📊 Etapas do Projeto
1. **Importação e exploração dos dados**  
   - Leitura do dataset de risco de crédito.  
   - Verificação de nulos, outliers e tipos de variáveis.  

2. **Análise exploratória (EDA)**  
   - Distribuições e correlações.  
   - Relação entre variáveis socioeconômicas e inadimplência.  

3. **Pré-processamento e engenharia de atributos**  
   - Tratamento de dados faltantes.  
   - Codificação de variáveis categóricas.  
   - Escalonamento e balanceamento das classes (SMOTE, se necessário).  

4. **Treinamento e avaliação de modelos**  
   - Modelos testados: *Logistic Regression, Random Forest, XGBoost*.  
   - Métricas de desempenho: *Accuracy, F1-Score, ROC-AUC, Matriz de Confusão*.  

5. **Conclusões e insights**  
   - Identificação das features mais relevantes para a previsão de inadimplência.  
   - Comparativo entre os modelos.  
   - Sugestões práticas para uso do modelo.

---

### ⚙️ Tecnologias Utilizadas
- **Python 3.10+**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn**, **Imbalanced-learn**
- **XGBoost** *(opcional)*
- **Jupyter Notebook**

---

### 🧩 Como Reproduzir o Projeto

1. **Clone o repositório**
   ```bash
   git clone https://github.com/TH1987-SANTOS/risco_credito.git
   cd risco_credito
