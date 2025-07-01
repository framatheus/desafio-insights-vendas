# Projeto: Análise de Vendas com Inteligência Artificial

Este projeto foi desenvolvido como parte do desafio da DIO, com o objetivo de aplicar técnicas de análise de dados e inteligência artificial para extrair insights estratégicos a partir de relatórios reais de vendas em marketplaces.

## Objetivo

Explorar o uso de prompts com ferramentas de inteligência artificial (como o ChatGPT) para analisar bases de dados, identificar padrões e gerar conclusões relevantes para o negócio, simulando a atuação prática de um analista de dados.

## O que foi feito

- Análise de 5 bases de dados com vendas realizadas em diferentes plataformas (Shopee, AliExpress, Etsy, entre outras);
- Geração de prompts estratégicos para explorar os dados;
- Extração de insights como produtos mais vendidos, ticket médio, sazonalidade e desempenho por canal;
- Organização dos resultados em arquivos prontos para consulta.

## Estrutura do Repositório

desafio-insights-vendas/
├── planilhas/
│ ├── Meganium_Sales_Data.csv
│ ├── Meganium_Sales_Data_-AliExpress.csv
│ ├── Meganium_Sales_Data-Etsy.csv
│ ├── Meganium_Sales_Data-_Shopee.csv
│ └── Updated_Anbernic_Sales_Data.csv
├── insights/
│ └── resumo_insights.md
├── prompts/
│ └── prompts_utilizados.md
└── README.md

## Exemplos de Prompts Utilizados

- "Quais os 5 produtos mais vendidos por unidade?"
- "Qual produto gerou a maior receita total?"
- "Existe sazonalidade nas vendas ao longo dos meses?"
- "Qual o ticket médio por pedido?"
- "Há produtos com alta visualização e baixa conversão?"

*Todos os prompts estão documentados no arquivo `/prompts/prompts_utilizados.md`.*

## Insights Gerados

- Produtos líderes em vendas por volume e por receita;
- Análise por mês para identificar sazonalidade;
- Ticket médio por canal;
- Comparativo de performance entre marketplaces.

*Todos os insights estão disponíveis no arquivo `/insights/resumo_insights.md`.*

## Ferramentas Utilizadas

- Python + Pandas
- Jupyter Notebook
- IA (ChatGPT) para geração e aplicação de prompts
- Git e GitHub

## Como Executar

1. Clone este repositório:
git clone https://github.com/framatheus/desafio-insights-vendas.git


Desenvolvido por Matheus Franchin no desafio da [DIO - Digital Innovation One](https://www.dio.me/).
