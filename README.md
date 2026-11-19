# Sistema de Análise de Vendas

Projeto prático de análise de dados desenvolvido em Python com as bibliotecas **Pandas** e **Matplotlib** para diagnosticar o desempenho comercial, financeiro e operacional de uma rede varejista (base `vendas.csv` com 50.000 registros).

## Objetivo
Realizar o tratamento e limpeza dos dados brutos, calcular indicadores de desempenho (KPIs), gerar visualizações gráficas e responder a perguntas estratégicas de negócio.

## Estrutura do Repositório
* [PROJETO_FINAL.ipynb](Projeto_Final/PROJETO%20FINAL/PROJETO_FINAL.ipynb) — Jupyter Notebook completo com códigos comentados, células explicativas (Markdown) e gráficos das Questões 1 a 11.
* `vendas.csv` — Base de dados utilizada nas análises (período de 2021 a 2023).

## Etapas Realizadas
1. **Exploração e Limpeza de Dados:** Remoção de 150 duplicados, preenchimento de valores ausentes, padronização de categorias, tratamento de datas inválidas e filtro de valores negativos (restando 49.552 registros válidos).
2. **Análise Financeira e Comercial:** Cálculo de faturamento bruto/líquido, ranking dos 10 produtos mais vendidos, desempenho por categoria e formas de pagamento.
3. **Sazonalidade, Equipe e Geografia:** Evolução mensal/anual (2021–2023), ranking dos 5 melhores vendedores com ticket médio e faturamento por estado (UF).
4. **Visualização e Estudo Aplicado:** Construção de 7 gráficos e cruzamento entre Estado x Categoria para recomendação de investimento.

## Principais Resultados
* **Faturamento Bruto (vendas concluídas):** R$ 117.190.025,60
* **Faturamento Líquido (vendas concluídas):** R$ 110.386.064,05
* **Categorias Líderes:** Informática (R$ 59,35 milhões) e Eletrônicos (R$ 43,60 milhões)
* **Estados com Maior Faturamento:** Paraná (PR), Santa Catarina (SC) e São Paulo (SP)
* **Recomendação Estratégica:** Concentrar o orçamento de marketing nas categorias de Informática e Eletrônicos nos estados do Sul (SC e PR) e Sudeste (MG e SP).

## Tecnologias Utilizadas
* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---
Desenvolvido por **Marcelo Sousa de Mendonça**
