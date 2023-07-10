# BikeSharing
Esse projeto tem como objetivo fazer um estudo de um dataset sobre bike sharing
e tentar criar um modelo que ajude a prever o número total de bicicletas que serão
alugadas a cada hora. O dataset se encontra no link:
● https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

Nesse projeto dividimos o dataframe em treino (dados de 2011) e teste (dados de 2012)
e usamos o OneHotEncoder para tranformar as variáveis qualitativas em dummies para em
seguida treinar os seguintes modelos de rede neural na base de treino e computar o valor do
MAE (mean absolute error) para cada um deles, usando a base de teste:
  1. Modelo sem nenhuma camada intermediária;
  2. Modelo com uma camada intermediária com 10 neurônios;
  3. Modelo com duas camadas intermediárias com 10 neurônios cada
