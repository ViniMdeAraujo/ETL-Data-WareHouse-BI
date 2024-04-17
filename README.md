Este repositório é uma demonstração de como manipular dados usando pandas e numpy. Ele cria e manipula dois conjuntos de dados: Produtos e Vendas.

Produtos: Cria um conjunto de dados de produtos com 600 produtos, incluindo produto_id, nome e categoria. Os dados são convertidos em um DataFrame e salvos em um arquivo CSV chamado produtos.csv.

Vendas: Cria um conjunto de dados de vendas com 1000 registros de vendas, incluindo data, produto_id, quantidade e valor_total. Os dados são convertidos em um DataFrame e salvos em um arquivo CSV chamado vendas.csv.

Manipulação de Dados: Os arquivos CSV são carregados de volta em DataFrames. Os DataFrames de vendas e produtos são mesclados com base em produto_id usando uma junção interna (inner join). O resultado é salvo em um arquivo CSV chamado data_warehouse.csv.

Visualização de Dados: O arquivo data_warehouse.csv é carregado novamente em um DataFrame chamado df_warehouse. O conteúdo do df_warehouse é exibido no console.

Este código ilustra como lidar com conjuntos de dados, realizar junções, salvar e carregar dados em arquivos CSV, e visualizar o resultado final.

Link para notebook Google Colab: https://colab.research.google.com/drive/1JOe8YQO0Z6dvBFWymhFqyMkLYRTRaKnS?usp=sharing

![image](https://github.com/ViniMdeAraujo/ETLDATAWAREHOUSE-BI/assets/127357097/e008ac2f-144d-4e32-bff1-ee6792373779)
