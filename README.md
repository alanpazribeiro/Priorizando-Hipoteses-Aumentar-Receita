# Priorizando Hipóteses para Aumento de Receitas marketing através do Teste A/B

# Objetivo do Projeto
Dentre as hipóteses apresentadas pelo setor de Marketing, priorizar através do Teste A/B aquelas que podem aumentar a receita.

# Bibliotecas Utilizadas
Pandas
Matplotlib
Numpy
Scipy
Math
Seaborn

# Descrição dos Dados:

1 - Dados usados na primeira parte do projeto

 - *Hypotheses* — breves descrições das hipóteses
 - *Reach* — alcance do usuário, em uma escala de um a dez
 - *Impact* — impacto nos usuários, em uma escala de um a dez
 - *Confidence* — confiança na hipótese, em uma escala de um a dez
 - *Effort* — os recursos necessários para testar uma hipótese, em uma escala de um a dez. Quanto maior o valor de Effort, mais recursos são necessários para o teste.

2 - Dados usados na segunda parte do projeto

 - *transactionId* — identificador do pedido
 - *visitorId* — identificador do usuário que fez o pedido
 - *date* — do pedido
 - *revenue* — do pedido
 - *group* — o grupo de teste A/B ao qual o usuário pertence
 - 
3 - Dados usados na terceira parte do projeto
 - *date* — data
 - *group* — grupo de teste A/B
 - visits* — o número de visitas na data especificada para o grupo de teste A/B especificado

A - Parte 1 - Priorizando Hipóteses

O arquivo hypotheses_us.csv contém nove hipóteses para aumentar a receita de uma loja online com Reach, Impact, Confidence e Effort especificados para cada um. A tarefa é:
 - Aplicar o framework ICE para priorizar hipóteses. Classifique-os em ordem decrescente de prioridade.
 - Aplicar o framework RICE para priorizar hipóteses. Classifique-os em ordem decrescente de prioridade.
 - Mostre como a priorização de hipóteses muda quando você usa RICE em vez de ICE. Dê uma explicação para as alterações.

B - Parte 2 - Análise de teste A/B

Você realizou um teste A/B e obteve os resultados descritos nos arquivos orders_us.csv e visitors_us.csv. A tarefa é:

 - Faça um gráfico da receita acumulada por grupo. Tire conclusões e crie conjecturas.
 - Faça um gráfico do tamanho médio acumulado do pedido por grupo. Tire conclusões e crie conjecturas.
 - Faça um gráfico da diferença relativa no tamanho médio acumulado do pedido para o grupo B em comparação com o grupo A. - Faça conclusões e crie conjecturas.
 - Calcule a taxa de conversão de cada grupo como a proporção de pedidos para o número de visitas para cada dia. Trace as taxas de conversão diárias dos dois grupos e descreva a diferença. Tire conclusões e crie conjecturas.
 - Faça um gráfico da diferença relativa na conversão cumulativa para o grupo B em comparação com o grupo A. Tire conclusões e crie conjecturas.
 - Calcule os percentis 95 e 99 para o número de pedidos por usuário. Defina o ponto em que um ponto de dados se torna uma anomalia.
 - Faça um gráfico de dispersão dos preços dos pedidos. Tire conclusões e crie conjecturas.
 - Calcule os percentis 95 e 99 dos preços dos pedidos. Defina o ponto em que um ponto de dados se torna uma anomalia.
 - Encontre a significância estatística da diferença na conversão entre os grupos usando os dados brutos. Tire conclusões e crie conjecturas.
 - Encontre a significância estatística da diferença no tamanho médio do pedido entre os grupos usando os dados brutos. Tire conclusões e crie conjecturas.
 - Encontre a significância estatística da diferença na conversão entre os grupos usando os dados filtrados.Tire conclusões e crie conjecturas.
 - Encontre a significância estatística da diferença no tamanho médio do pedido entre os grupos usando os dados filtrados. Tire conclusões e crie conjecturas.
 - Tome uma decisão com base nos resultados do teste. As decisões possíveis são: 1. Pare o teste, considere um dos grupos o líder. 2. Pare o teste, conclua que não há diferença entre os grupos. 3. Continue o teste.
