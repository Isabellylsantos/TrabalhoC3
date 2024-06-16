Projeto de Análise e Modelagem de Preços de Casas

Descrição do Projeto
Este projeto envolve a análise exploratória, pré-processamento, redução de dimensionalidade e modelagem de dados de preços de casas utilizando um conjunto de dados público do Kaggle.
O objetivo é entender a variabilidade nos dados, aplicar técnicas de aprendizado supervisionado e não supervisionado, e avaliar o desempenho dos modelos.

Ferramentas e Bibliotecas Utilizadas
Bibliotecas de Python: numpy, pandas, matplotlib, seaborn, scikit-learn.
Modelos de Machine Learning: Regressão Logística.

Passos do Projeto

1. Carregar e Analisar os Dados
Carregamos os dados de treinamento e realizamos uma análise exploratória inicial para identificar variáveis categóricas e numéricas, além de verificar valores faltantes.

2. Visualização dos Dados
Visualizamos a distribuição das variáveis numéricas, incluindo outliers, e plotamos a distribuição da variável alvo SalePrice.

3. Redução de Dimensionalidade com PCA
Aplicamos PCA para reduzir a dimensionalidade dos dados e visualizar os componentes principais.

4. Modelagem e Avaliação de Desempenho
Treinamos e avaliamos vários modelos de aprendizado supervisionado, incluindo Regressão Logística.

5. Comparação de Desempenho
Comparação dos modelos utilizando as métricas de desempenho e curvas ROC.

Resultados

    PCA:
        O primeiro componente principal captura aproximadamente 20.33% da variância total nos dados.
        O segundo componente principal captura aproximadamente 8.43% da variância total.
        Os componentes principais mostram uma correlação com SalePrice.

    Curva ROC:
        A curva ROC mostra um desempenho excelente dos modelos, especialmente a Regressão Logística com uma AUC de 0.98.
        Comparação visual das curvas ROC indica que todos os modelos têm um bom desempenho na distinção entre as classes.

Conclusão
O projeto demonstra como técnicas de redução de dimensionalidade e modelos de aprendizado supervisionado podem ser aplicados para entender e prever os preços das casas. A avaliação das métricas de
desempenho e a visualização das curvas ROC ajudam a comparar e selecionar o modelo mais eficaz.

Referências
Kaggle Dataset

Bibliotecas: numpy, pandas, matplotlib, seaborn, scikit-learn














