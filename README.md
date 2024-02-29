# Predição de Valores de Retorno em Relação ao Investimento em Marketing
  Uma empresa está investindo mensalmente em plataformas de publicidade online, como Youtube, Facebook e newspaper, para a prospecção de leads (pessoas interessadas em seus produtos). A fim de acompanhar o desempenho desses
investimentos, a empresa registra todos os gastos com publicidade e todos os retornos de vendas gerados a partir desses investimentos. Para entender melhor a relação entre as variáveis presentes nesses registros e identificar os fatores que mais impactam na geração de leads, a empresa solicitou uma análise de dados. Além disso, a empresa busca criar um modelo de predição de valores para estimar o retorno de vendas que pode ser gerado a partir de um determinado investimento em publicidade.

## 🚀 Análise Descritiva:
 Esta etapa consiste em explorar os dados do dataset para compreender melhor as variáveis e identificar problemas. Para isso, é foi utilizada a biblioteca Pandas para importar, manipular e realizar cálculos estatísticos com os dados, além das bibliotecas de visualização.

 O primeiro passo foi visualizar a base de dados:
  
  ![image](https://github.com/juanlucas7/Regressao_Marketing/assets/149596266/1b37a73f-510d-4bf7-ace5-54abf62486f7)

  O segundo passo foi utilizar a função de 'describe' e ver algumas informações adicionais:

  ![image](https://github.com/juanlucas7/Regressao_Marketing/assets/149596266/0255129b-5f02-462b-b7ad-41ddea927033)

  E por último, foi verificado se existiam valores nulos.

## 🕵🏾 Análise Exploratória:
  Nesta etapa os dados vão ser explorados de uma maneira mais profunda, identificando relações entre as variáveis e descobrindo padrões relevantes.

  Para identificar padrões de linearidade, foi utilizada uma função da biblioteca "seaborn" chamada de  Pairplot. Com isso, foram gerados uma série de gráficos afim de verificar tais informações de forma mais visual:
  
 ![image](https://github.com/juanlucas7/Regressao_Marketing/assets/149596266/b64bca86-53a3-4fc3-93da-fbfd88b32fe5)

