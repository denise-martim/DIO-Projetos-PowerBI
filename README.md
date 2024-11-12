# DIO-Projetos-PowerBI
Projetos de Power BI desenvolvidos nos cursos da DIO.

## Projeto 1

- Relatório de Vendas Considerando Produtos e Segmento
- Relatório de Vendas Considerando Países e Lucro
- Distribuição de Lucro, Vendas e Unidades Vendidas por País e Segmento

## Projeto 2

- Sales Report
- Report de Lucro Detalhado

## Projeto 3

Realizado tratamento de dados, como tipos de colunas, e transformações de dados como:
- Separação de colunas complexas e mescla de nomes.
- Mescla das consultas employee e departament para criação de tabela com o nome dos departamentos associados aos colaboradores.
- Mescla de departamentos e suas localizações.
- Associação de managers com seus respectivos employees.
- Eliminação de colunas desnecessárias.

## Projeto 4 
Criação de diagrama Star Schema com base no diagrama relacional disponibilizado em aula.

## Projeto 5
A partir da base financials foram criadas as tabelas dimensão e a tabela fato, em modelo star schema conforme imagem do diagrama.

As tabelas tratadas foram: 
- D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)
- D_Produtos_Detalhes (ID_produtos, Discount Band, Sale Price, Units Sold, Manufactoring Price)
- D_Descontos (ID_produto, Discount, Discount Band)
- D_Detalhes (Discount Band, ID Produto, Indice, Manufacturing Price, Product, Sale Price, Units Sold)
- D_Calendário – Criada por DAX com calendar()
- F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount Band, Segment, Country, Salers, Profit, Date (campos))

Foram criadas as colunas de índices de produtos através de coluna condicional, realizado agrupamento de contagem, valor mínimo, máximo, média e mediana de vendas e média de manufatura.
E criação da tabela D_Calendário por DAX com calendar().

## Projeto 6

Atualizações no projeto de Sales Report com Foco na Experiência do Usuário.
- Incluídos botões de navegabilidade para cada página
- Modificações na segunda página de forma similar demonstrada no desafio para a primeira página.

## Projeto 7 

- Criado Home Page para apresentação do Report Financeiro com navegabilidade.
- Página Sales Report com visuais de Total de Vendas, Unidades Vendidas, Soma discounts e Soma COGS, Vendas por Período, Sales x Segment, Vendas x Produto, soma de vendas por país.
- Detalhes de Vendas apresenta visuais de vendas x semestre, tabela valores totais por trimestre/ano, histograma de unidades vendidas, valores vendidos x produtos.
- TOPN & Clusters & Outlier com visuais de clusterização, outlier, TOP3 Produtos, TOP3 produto por país e TOP3 profit por mês.

## Projeto 8 

- Seguindo o que foi feito no projeto 7 e com o intuito de criação de relatórios dinâmicos com o uso de parâmetros no Power BI, foi adicionada uma nova página contendo duas visões:
  - parâmetro com base em categorias
  - parâmetros com base em valores
