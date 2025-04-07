# 🚢 Modelo Preditivo com Regressão Logística  
### 🎯 Previsão de Sobrevivência no Titanic

Este repositório contém um projeto de aplicação de **regressão logística** para prever a sobrevivência dos passageiros do Titanic com base em dados reais. O objetivo é treinar um modelo de **classificação binária** utilizando variáveis como idade, sexo, classe da passagem, entre outras.

📌 Projeto desenvolvido durante o **Bootcamp de Inteligência Artificial LLM da SoulCode**.

---

## 🛠 Tecnologias Utilizadas

- Python 3  
- Pandas  
- NumPy  
- Scikit-learn  
- Seaborn  
- Matplotlib  
- Google Colab  
- GitHub  

---

## 🧠 O que o código faz?

1. **Carregamento do Dataset**  
   - Utilizado o dataset público **Titanic** (Kaggle).  
   - A variável alvo (`Survived`) indica se o passageiro sobreviveu (1) ou não (0).

2. **Análise Exploratória e Limpeza dos Dados**  
   - Remoção de colunas irrelevantes (como "Cabin", "Ticket", etc).  
   - Tratamento de valores ausentes e conversão de variáveis categóricas.  
   - Visualização com gráficos (por sexo, classe, idade, etc).

3. **Modelagem com Regressão Logística**  
   - Separação dos dados em treino e teste.  
   - Treinamento com o modelo `LogisticRegression()` do Scikit-learn.

4. **Avaliação do Modelo**  
   Avaliação usando as seguintes métricas:
   - ✅ **Acurácia**: 80%  
   - 🎯 **Precisão**: 0.83 (para não sobreviventes), 0.74 (para sobreviventes)  
   - 🔁 **Recall**: 0.82 (não sobreviventes), 0.76 (sobreviventes)  
   - 📏 **F1-Score**: equilibrado (0.83 e 0.75)  
   - 📊 Visualização da **matriz de confusão** e **gráficos** para facilitar a interpretação.

---

## 📊 Resultados

- **Relatório de Classificação:**

```plaintext
              precision    recall  f1-score   support

           0       0.83      0.82      0.83       128
           1       0.74      0.76      0.75        87

    accuracy                           0.80       215
   macro avg       0.79      0.79      0.79       215
weighted avg       0.80      0.80      0.80       215
```

- **Interpretação**:  
  O modelo teve bom desempenho, com acurácia geral de **80%**.  
  Ele se mostrou levemente mais eficiente para prever **não sobreviventes** (classe 0), mas ainda assim apresentou um **recall de 76% para sobreviventes**, o que é positivo.  
  O **F1-score equilibrado** mostra que há harmonia entre precisão e sensibilidade.

- **Gráficos Gerados**:
  - Matriz de Confusão  
  - Gráfico de Precisão, Recall e F1-score  
  - Gráfico de comparação entre as classes preditas e reais

---

## 🚀 Como executar o projeto

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/projeto-titanic-regressao-logistica
```

2. Instale as dependências (caso rode localmente):

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

3. Execute o notebook no **Jupyter** ou **Google Colab**  
👉 [https://colab.research.google.com/drive/1_4AwwJmASyElrxk0QU_OpIKWA3lE3otN?usp=sharing](#)

---

## 📽 Apresentação

Em construção. (Se quiser, posso montar no Canva contigo!)

---

## 📜 Licença

Projeto educacional, desenvolvido durante o Bootcamp de IA LLM da SoulCode.
