# Análise de Dados com as Bases da Contoso

Neste notebook, fazemos uma análise dos dados de negócio da Contoso, uma empresa fictícia criada pela Microsoft. Temos as seguintes bases de dados:

- Cadastro de Produtos
- Cadastro de Clientes
- Cadastro de Lojas
- Registros de Vendas de 2017

Inicialmente, importamos as bases de dados como **dataframes** do pandas e visualizamos suas primeiras linhas com o método `.head()` a fim de nos situarmos. Em seguida, realizamos uma limpeza dos dados, removendo colunas vazias e colunas desnecessárias para os propósitos da análise. Por fim, na última etapa de tratamento, mesclamos os dataframes num único dataframe chamado `df_vendas`.

O objetivo desta análise é encontrar as respostas para as seguintes perguntas:

1. Qual o cliente que comprou mais vezes?

2. Qual a loja que mais vendeu?

3. Qual o produto que menos vendeu?

4. Qual o percentual de vendas que foram devolvidas?

5. Qual foi o percentual de devoluções da Loja Contoso Europe Online?

6. Quantas vendas da Loja Contoso Europe Online não tiveram devoluções?
