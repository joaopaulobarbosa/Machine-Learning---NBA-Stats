### Quadro geral:
1. **Obtenção dos dados**:
   - Carregamento e visualização inicial dos dados.

2. **Exploração dos dados**:
   - Análise exploratória para entender o formato e os principais aspectos dos dados.
   - Visualização de distribuições, análise de valores ausentes e outliers.
   - Avaliação de correlações entre features, com foco nas correlações mais fortes, especialmente em relação à variável de interesse (provavelmente salário).

3. **Limpeza dos dados**:
   - Eliminação de outliers.
   - Transformações para limpar e padronizar os dados.

4. **Preparação dos dados**:
   - Escolha das features relevantes para o treinamento de modelos.
   - Análise de correlações com novas features após transformação dos dados.

5. **Seleção e treinamento de modelo - Regressão Linear**:
   - Treinamento de um modelo de regressão linear para prever salários.
   - Análise de erros e superfaturamento.
   - Visualização dos resíduos e ajuste do modelo.

6. **Seleção e treinamento de modelo - Random Forest**:
   - Treinamento de um modelo Random Forest com busca de hiperparâmetros.
   - Mesma análise feita para a Regressão Linear (superfaturamento, resíduos, erro acumulado).

7. **Seleção e treinamento de modelo - XGBoost**:
   - Treinamento de um modelo XGBoost, novamente com busca de hiperparâmetros.
   - Análise similar às etapas anteriores (previsão vs real, resíduos, erro acumulado, ajuste final).

8. **Conclusões finais**:
   - Comparação de desempenho entre os modelos (Linear Regression, Random Forest, XGBoost).
   - Conclusões sobre o modelo mais adequado para o problema em questão.
