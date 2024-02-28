# Detecção de Fraudes em Cartões de Crédito utilizando Machine Learning
<img width="65%" src="https://raw.githubusercontent.com/AAndreo/Deteccao.Fraude.Cartao.Credito/main/Arquivos/fraude.jpg">
Imagem de <a href="https://br.freepik.com/vetores-gratis/roubar-o-conceito-de-ataque-cibernetico-de-dados_7970626.htm#query=credit%20card%20fraud&position=33&from_view=search&track=ais">Freepik</a>

## Sobre
No Brasil em 2022 registrou R$5,8 bilhões em tentativas de fraudes. Segundo dados da ClearSale, empresa especialista em prevenção e gerenciamento de risco, o mapa da fraude revelou 5,6 milhões de tentativas no período de 1º de janeiro a 31 de dezembro. O estudo analisou 312,2 milhões de pedidos no e-commerce brasileiro, feitos via pagamento por cartão de crédito. Em comparação com o ano anterior, as tentativas de fraude apresentaram uma queda de 0,3%, mas os valores ainda foram 4,8% maiores do que em 2021.

Sobre as regiões, assim como no ano anterior, a região Norte segue na dianteira, com o maior índice de tentativas de fraude sobre a quantidade total de transações, sendo 3,4%. Ela também é a primeira no ranking do ticket médio da tentativa de fraude com o valor de R$1.420,00. Seguida pelo Nordeste (2,8%); Centro Oeste (2,5%), Sudeste (2,1%) e Sul (1,1%).

A detecção de fraudes em cartões de crédito é um campo crucial para a segurança financeira dos consumidores e das instituições financeiras. As fraudes em cartões de crédito ocorrem quando atividades não autorizadas são realizadas em uma conta de cartão de crédito, resultando em perdas financeiras para os titulares dos cartões ou para os emissores dos cartões.

## Descrição
Utilizando uma base de dados anônimos de operações realizadas por cartões de crédito no período de 48 horas, foi realizado todo processo de análise de dados, pré-processamento e avaliação dos nossos algoritmos de aprendizado para classificação, buscando mecanismos eficientes que garantam precisão na detecção de fraudes e quantidade de falsos negativos.
  * [Projeto completo](Deteccao_Fraude_Cartao_Credito.ipynb)

## Nossos dados
Esse [dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) contem dados anonimos de operações realizadas por cartões de crédito, no periodo de Setembro de 2013, por titulares de cartões europeus. Os registros apresentam 284.807 transações realizadas em dois dias, onde ocorreram 492 fraudes.
As features independentes são todas numéricas, onde a sua grande maioria é o resultado de uma transformação PCA.

A análise de componentes principais (PCA) é uma técnica que transforma dados de alta dimensão em dimensões inferiores, mantendo o máximo de informações possível.

Por questões de segurança e confidencialidade, não foram fornecidos os dados originais, bem como, mais informações sobre os mesmos.
As features que são representadas por V1, V2, V3, ... V28, são as que sofreram a transformação pelo processo PCA.

## **Nosso desafio**
* Transações fraudulentas com cartões de crédito.
  
## **Qual é o objetivo?**
* Identificar essas transações de forma eficaz.

## **Como?**
* Criando e aperfeiçoando mecanismos eficientes, através da análise exploratória dos dados disponibilizados e modelos de machine learning. Além disso, para a avaliação da eficácia dos modelos construidos, analisar os resultados de métricas que garantam precisão na detecçao de fraudes e quantidade de falsos negativos.
