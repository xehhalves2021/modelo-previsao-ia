
# Modelo de Previsão - KNN no Dataset Iris

Este repositório contém um modelo de previsão utilizando o algoritmo **K-Nearest Neighbors (KNN)** para classificar flores no famoso **dataset Iris**.

## Passos para Treinamento do Modelo

1. **Importação das Bibliotecas**
   - Usei **Scikit-learn**, **Pandas**, e **Matplotlib** para importar, treinar e visualizar os dados.

2. **Carregamento e Pré-processamento dos Dados**
   - Carreguei o dataset Iris usando a função `datasets.load_iris()` do **Scikit-learn**.
   - Dividi os dados em **treinamento (70%)** e **teste (30%)**.

3. **Treinamento do Modelo**
   - O modelo **K-Nearest Neighbors** foi treinado com o conjunto de dados de treinamento.

4. **Avaliação e Salvamento do Modelo**
   - Avaliei o modelo usando a métrica de **precisão**, que resultou em uma acurácia de **100%**.
   - Após isso, salvei o modelo treinado no arquivo `modelo_knn_iris.pkl`.

## Como Usar

1. Clone este repositório.
2. Instale as dependências com o comando:
   ```bash
   pip install -r requirements.txt
   ```
3. Para carregar o modelo e fazer previsões, basta usar o seguinte código:
   ```python
   import joblib
   model = joblib.load('modelo_knn_iris.pkl')
   ```

## Dependências
- pandas
- scikit-learn
- matplotlib
