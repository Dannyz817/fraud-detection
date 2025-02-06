# Credit Card Fraud Detection Dataset (2023)
Este repositório contém um modelo de aprendizado de máquina para detecção de fraudes em transações com cartão de crédito, utilizando o dataset disponível no Kaggle:
https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023

Este conjunto de dados contém transações com cartão de crédito feitas por titulares de cartão europeus no ano de 2023. Ele compreende mais de 550.000 registros, e os dados foram anonimizados para proteger a identidade dos titulares dos cartões. O principal objetivo deste conjunto de dados é facilitar o desenvolvimento de algoritmos e modelos de detecção de fraudes para identificar transações potencialmente fraudulentas.

#### Algumas das principais colunas incluem:
- id - Identificador único para cada transação.
- V1-V28 - Atributos anonimizados representando várias características da transação (ex.: tempo, localização, etc.).
- Amount - Valor da transação.
- Class - Rótulo binário indicando se a transação é fraudulenta (1) ou não (0).

### 📈 Modelagem
- Modelo Principal: Regressão Logística
- Ajuste de Limiar: Reduzido para aumentar a sensibilidade e detectar mais fraudes
- Avaliação: Acurácia, Precisão, Recall, F1-score e Matriz de Confusão

No código desenvolvido, foi realizado a análise exploratória dos dados, verificando distribuições e padrões. Em seguida, foram aplicadas técnicas de pré-processamento, como normalização. Para a modelagem, foi utilizado um modelo de regressão logística, ajustando o limiar de decisão para aumentar a sensibilidade na detecção de fraudes. Por fim, foram geradas métricas de avaliação, incluindo matriz de confusão, e visualizações gráficas para interpretação dos resultados.
