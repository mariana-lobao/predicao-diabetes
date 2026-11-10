# predição de diabetes

## Sobre o projeto: 
Este projeto tem como objetivo colocar em prática meus aprendizados na minha pós-graduação em ciência de dados aplicada à saúde e desenvolver um modelo de classificação capaz de prever se um paciente é ou não diabético, com base em suas características e informações clínicas.

## Tecnologias utilizadas:
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

## Etapas do projeto:
- Exploração inicial da estrutura de dados
- Verificação de valores nulos
- Verificação e remoção de registros duplicados
- Análise exploratória dos dados (EDA): investigação das características dos dados e da distribuição das classes.
- Pré-processamento: tratamento das variáveis categóricas com One-Hot Encoding e padronização dos dados com StandardScaler
- Treinamento dos modelos: utilização de Regressão Logística e Random Forest, incluindo testes com balanceamento de classes e alteração do threshold.
- Avaliação dos modelos: comparação dos resultados utilizando accuracy, precision, recall, F1-score, ROC-AUC e PR-AUC.

## Principais resultados:
Foram avaliadas diferentes abordagens de classificação, considerando o desbalanceamento entre as classes.
A Regressão Logística apresentou ROC-AUC de 0,960, enquanto o Random Forest apresentou ROC-AUC de 0,959 e PR-AUC de 0,852.
Nenhum dos modelos apresentou desempenho superior em todas as métricas. A escolha depende do objetivo da aplicação e da importância atribuída aos falsos positivos e falsos negativos. Em um contexto de triagem de diabetes, por exemplo, um recall mais elevado pode ser desejável para reduzir a quantidade de casos positivos não identificados.

## Limitações:
Este projeto foi desenvolvido para fins de estudo. Portanto, os resultados não devem ser utilizados na prática clínica para diagnosticar diabetes, pois os modelos ainda precisariam de validações adicionais.

## Fonte dos dados:
Foi utilizada a base de dados Diabetes Prediction Dataset, disponibilizada no Kaggle.
https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
