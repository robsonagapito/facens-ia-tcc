# FACENS - TCC
Trabalho de TCC da Facens - Pós Graduação em Inteligência Articial Aplicada e Machine Learning

Ano:2022

## TEMA
PREVISÃO EM UM SISTEMA DE VENDAS COMERCIAL A PARTIR DE ALGORITMOS DE INTELIGÊNCIA ARTIFICIAL

## AUTORES
Henrique Seschin Neto - RA:202083

Robson Agapito Correa - RA:202062

## RESUMO
Atualmente, no período pós pandemia, propiciou que as lojas de colchões e estofados, pudessem aumentar sua visibilidade e vendas, através de ferramentas e comunicadores digitais. Devido a grande quantidade de informações registradas diariamente em um sistema de vendas de uma loja de colchões em Sorocaba-SP, o controle se tornou mais complexo, sendo que o sistema atual possui certas dificuldades para extrair informações relevantes e encontrar probabilidades de possíveis vendas futuras. 

Este trabalho propôs uma solução para extrair essas informações da base de dados da loja e tem como tarefa encontrar previsões das vendas futuras, através de algoritmos de inteligência artificial. 

Teve-se como objetivo neste trabalho, inserir técnicas de categorização de textos, pré-processamento de dados, redução de dimensionalidade e técnica para a diminuição do desbalanceamento das classes, para isto ocorrer, empregou-se o uso das técnicas Bag-of-Words, OrdinalEncoder, PCA e SMOTE. 

Para encontrar as previsões das vendas desse sistema, foram aplicados os métodos de classificação XGBoost, LightGBM, RandomForest e uma simples arquitetura de Rede Neural Artificial (RNA). Foram realizadas comparações sobre qual método de classificação obteve o melhor desempenho nas predições, avaliados através das métricas de validação F1-Score, Macro Average, Predict_Proba e Accuracy. Apesar do método XGBoost ter apresentado excelentes resultados quando seus dados foram treinados com a técnica do Bag-of-Words, ele se torna computacionalmente caro, quando treinado com grandes Datasets e também é mais lento do que o método LightGBM. 

Sugere-se para futuros trabalhos, usar uma base de dados maior e que esteja padronizada, para possibilitar a redução do desbalanceamento dos dados e também se sugere, buscar através da técnica GridSearch, por melhores hiperparâmetr
