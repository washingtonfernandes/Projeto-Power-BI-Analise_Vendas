 
# Lab 2: Dashboard de Vendas, Custo, Margem de Lucro e KPI

Este projeto foi desenvolvido como parte do curso **Microsoft Power BI Para Business Intelligence e Data Science** da [Data Science Academy](https://www.datascienceacademy.com.br).

## Visão Geral
O objetivo deste laboratório é construir um dashboard interativo para análise de métricas financeiras e comerciais. O painel fornece uma visão clara sobre o volume de vendas, custos operacionais e margem de lucro, utilizando Indicadores-Chave de Desempenho (KPIs) para facilitar a tomada de decisão estratégica.

<img width="886" height="509" alt="image" src="https://github.com/user-attachments/assets/7338c2a2-3863-48d2-82a1-30724861ff7d" />
##  Tecnologias e Conceitos Aplicados
Durante a construção deste projeto, foram exploradas rotinas fundamentais de Business Intelligence:
* **Limpeza e Transformação de Dados:** Utilização dos recursos nativos do Power BI (Power Query) para tratar e preparar os datasets.
* **Modelagem de Dados:** Estruturação otimizada das tabelas para o ambiente analítico.
* **Cardinalidade:** Definição e gerenciamento dos relacionamentos entre tabelas (Fato e Dimensão).
* **Linguagem DAX:** Introdução e aplicação de *Data Analysis Expressions* para a criação de medidas e cálculos personalizados.

## Perguntas de Negócio Resolvidas
O modelo de dados e as visualizações foram construídos para responder estrategicamente às seguintes questões:
1. **Total de vendas por modo de envio:** Qual foi o total de valor de venda considerando cada modalidade de envio dos pedidos? *(Visualizado através de um Gráfico de Cascata).*
2. **Custo de envio por mercado:** Quais mercados apresentaram o maior custo médio de envio dos produtos vendidos? *(Visualizado através de um Gráfico Treemap).*
3. **Acompanhamento de Metas (KPI):** A empresa atingiu a meta de manter uma média de 350 para o valor de venda mensal? *(Inclui análise específica do desempenho no mês de Abril/2014).*
4. **Análise de Lucratividade:** Qual categoria de produto apresentou o maior lucro médio? *(Considerando o Lucro como: `Valor Venda - Custo Envio`).*
5. **Evolução da Margem de Lucro:** Qual foi o comportamento da margem de lucro ao longo do tempo? *(Considerando a Margem de Lucro como: `Lucro / Valor Venda`).*
## Como visualizar este projeto
1. Faça o download do arquivo `.pbix` disponível neste repositório.
2. Certifique-se de ter o **Microsoft Power BI Desktop** instalado em sua máquina.
*Projeto construído para aprimoramento prático em Data Science e Business Intelligence.*
