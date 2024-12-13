# **Previsão de Sobrevivência no Titanic**

Este projeto utiliza técnicas de machine learning para prever a sobrevivência de passageiros no Titanic com base em informações demográficas e socioeconômicas. O conjunto de dados utilizado é parte do famoso desafio do Kaggle: Titanic - Machine Learning from Disaster. O projeto inclui desde análise exploratória dos dados até o treinamento e avaliação de modelos de classificação.

---

## **Estrutura do Projeto**

A estrutura do projeto está organizada da seguinte maneira:

- **MVP_PUC_Daniel_Szyfman.ipynb**: Contém o notebook principal com todo o fluxo do projeto, incluindo análise exploratória, processamento, modelagem e avaliação.
- **requirements.txt**: Lista todas as dependências necessárias para executar o projeto.
---

## **Como Executar**

### **1. Clone o repositório**
```bash
git clone https://github.com/Szyfman/MVP_PUC_ML_1.git
cd MVP_PUC_ML_1
```

### **2. Crie um ambiente virtual Python e ative-o**
```bash
python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`
```

### **3. Instale as dependências**
```bash
pip install -r requirements.txt
```

### **4. Abra o notebook no Google Colab ou localmente**
- **No Google Colab**: Faça o upload do notebook `MVP_PUC_Daniel_Szyfman.ipynb` para o ambiente do Colab e execute as células conforme necessário.
- **Localmente**: Abra o arquivo com o Jupyter Notebook ou JupyterLab:
  ```bash
  jupyter notebook MVP_PUC_Daniel_Szyfman.ipynb
  ```

---

## **Resultados do Projeto**

O modelo **Gradient Boosting** foi o melhor classificador, com uma acurácia de 81% no conjunto de teste. Outras métricas como precision, recall e f1-score mostraram um bom equilíbrio entre classes, e a análise da curva ROC resultou em uma AUC de 0.89, indicando boa capacidade discriminativa.

---

## **Aprendizados e Próximos Passos**

- **Aprendizados:** O projeto reforçou a importância de um pré-processamento adequado e da seleção criteriosa de variáveis para alcançar bons resultados em problemas de classificação.
- **Próximos Passos:**
  1. Implementar um ensemble de modelos para melhorar a robustez das previsões.
  2. Aplicar metodologias similares a outros problemas de classificação binária.

---
