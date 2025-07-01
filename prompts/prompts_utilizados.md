# Prompts Utilizados na Análise de Vendas com IA

Este documento reúne os principais prompts utilizados com ferramentas de inteligência artificial para gerar insights a partir das planilhas de vendas fornecidas no desafio da DIO.

## Prompt 1 – Produtos mais vendidos em volume
**Objetivo:** Identificar os produtos com maior quantidade de vendas.

## Prompt 2 – Produtos com maior receita
**Objetivo:** Saber quais produtos mais geraram receita total.

## Prompt 3 – Média de vendas por mês
**Objetivo:** Entender o comportamento mensal das vendas.

## Prompt 4 – Ticket médio por pedido
**Objetivo:** Saber quanto cada cliente gastou, em média, por pedido.

## Prompt 5 – Identificação de sazonalidade
**Objetivo:** Descobrir meses de pico ou queda nas vendas.

## Prompt 6 – Produtos com alto interesse e baixa conversão (opcional)
**Objetivo:** Analisar se há produtos muito visualizados mas pouco vendidos.

## Adaptações feitas

Durante a análise, os nomes das colunas foram adaptados para refletir o conteúdo real das planilhas:

- Produto: `product_sold`
- Quantidade: `quantity`
- Receita total: `total_price`
- Data: `date`
- Pedido: `invoice_id`

## Ferramentas utilizadas

- ChatGPT para estruturação de prompts;
- Python + Pandas para execução dos cálculos;
- Jupyter Notebook para análises exploratórias;
- GitHub para documentação e versionamento.