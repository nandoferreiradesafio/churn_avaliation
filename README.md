# README – Análise de Performance Comercial

## Descrição do Projeto

Este projeto tem como objetivo organizar, analisar e gerar insights sobre a performance do time de vendas, utilizando dados históricos sobre transações, vendedores, planos e taxas de churn. A partir da análise, são feitas recomendações estratégicas para melhorar os resultados comerciais, apoiar a liderança na tomada de decisão e identificar padrões relevantes no comportamento dos clientes.

## Estrutura do Projeto

- Fonte de Dados: Arquivo estruturado no Google Sheets com métricas organizadas por mês e por vendedor.
- Ferramentas Utilizadas:
  - Python (para limpeza, transformação e análise dos dados)
  - Jupyte Notebook (Local das Transformações)
  - Google Sheets (armazenamento e organização final)
  - Looker Studio (criação de dashboards e visualizações interativas)

## Métricas Calculadas

- Quantidade total de vendas (por mês, por vendedor)
- Receita total, MRR e NRR
- Churn rate médio (mensal, por plano, por vendedor)
- Distribuição dos tipos de planos vendidos
- Categorias de desempenho de vendedores (abaixo da meta, próximo da meta, atingiu a meta)
- Percentual e valor de comissionamento aplicado (1% até 10 vendas; 1,5% a partir de 30 vendas)

## Principais Insights Identificados

- Vendedores com maior volume geram receitas significativamente maiores, mas nem sempre maior diversificação de planos implica em melhores resultados.
- Planos anuais apresentam menor churn, sugerindo potencial para aumentar retenção.
- A dependência excessiva de poucos vendedores e poucos planos aumenta os riscos operacionais.
- Há possíveis falhas ou rupturas temporais nos dados a partir de setembro de 2022 que precisam ser investigadas.

## Relatórios Criados

- Google Sheets: Organização detalhada dos dados, agrupados por vendedor e por mês, incluindo todas as métricas-chave.
- Looker Studio: Dashboard visual destacando principais métricas mensais, desempenho individual e geral, churn, receita e comparações entre planos.

## Recomendações para Próximos Passos

- Refinar os cálculos de comissão considerando os limites definidos e verificar impacto financeiro.
- Explorar campanhas de upsell direcionadas a clientes com MRR baixo/médio.
- Incentivar a migração para planos anuais para reduzir churn.
- Reavaliar métricas agrupadas, como churn rate, para aumentar a granularidade e precisão das análises.
- Investigar a interrupção de registros após setembro de 2022 e corrigir possíveis falhas de ingestão.
