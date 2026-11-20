<img width="2752" height="1536" alt="capa" src="https://github.com/user-attachments/assets/e58a08a1-f8ca-433b-ade9-271e61133fc6" />


# Projeto de análise de dados feito em Python usando **Pandas** e **Matplotlib** para ver como estão as vendas, o faturamento e a equipe de uma loja de varejo (usando a planilha `vendas.csv` com 50.000 linhas).

## Objetivo
Limpar a base de dados que veio com erros, calcular os totais de vendas, fazer os gráficos e tirar conclusões práticas para ajudar a empresa a vender mais.

## Arquivos do Projeto
- [PROJETO_FINAL.ipynb](Projeto_Final/PROJETO%20FINAL/PROJETO_FINAL.ipynb) — Arquivo do Jupyter Notebook com todos os códigos, explicações em texto e gráficos das Questões 1 a 11.
- `vendas.csv` — Planilha com os dados de vendas de 2021 até 2023.

## O que foi feito no projeto
1. **Limpeza dos Dados:** Tirei 150 linhas repetidas, preenchi cidades vazias com "Não Informada", arrumei palavras sem acento nas categorias, apaguei datas erradas e tirei quantidades e valores negativos (ficando 49.552 vendas válidas).
2. **Contas de Vendas e Produtos:** Calculei o faturamento bruto e líquido, listei os 10 produtos mais vendidos, vi qual categoria dá mais dinheiro e como os clientes preferem pagar.
3. **Meses, Vendedores e Estados:** Olhei as vendas por mês e por ano (2021 a 2023), os 5 melhores vendedores com o ticket médio de cada um e os estados que mais compram.
4. **Gráficos e Estudo Final:** Fiz 7 gráficos para mostrar os resultados e cruzei Estado com Categoria para decidir onde investir dinheiro.

## Principais Resultados
- **Faturamento Bruto (só vendas concluídas):** R$ 117.190.025,60
- **Faturamento Líquido (já tirando descontos):** R$ 110.386.064,05
- **Categorias que mais vendem:** Informática (R$ 59,35 milhões) e Eletrônicos (R$ 43,60 milhões)
- **Estados que mais compram:** Paraná (PR), Santa Catarina (SC) e São Paulo (SP)
- **Onde investir:** Focar o dinheiro de marketing em Informática e Eletrônicos nos estados do Sul (SC e PR) e Sudeste (MG e SP).

## O que a empresa pode fazer para melhorar as vendas
Com base nos números que achei na análise, as melhores ações para aumentar o lucro são:

1. **Diminuir cancelamentos, devoluções e pedidos pendentes (Recuperar até R$ 18,9 milhões):**
   - Quase 11% dos pedidos foram cancelados (7,85%) ou devolvidos (3,14%), o que dá R$ 13,82 milhões perdidos. Outros 3,90% ficaram parados como Pendente (R$ 5,10 milhões).
   - **O que fazer:** Entrar em contato rápido com quem deixou boleto ou cartão pendente para fechar a venda e melhorar a conferência na entrega para evitar devoluções.

2. **Fazer combos (Kits) de Informática/Eletrônicos com Acessórios/Áudio:**
   - Informática e Eletrônicos trazem mais de 93% do dinheiro, mas itens como Teclado e Mouse saem em grande quantidade com preço baixo (média de R$ 520 a R$ 536).
   - **O que fazer:** Vender kits com desconto (por exemplo: comprar um Notebook ou Monitor e levar Mouse, Teclado ou Fone com 10% de desconto) para aumentar o valor de cada compra.

3. **Investir mais propaganda nos estados fortes e dar frete grátis nos mais fracos:**
   - Sul (PR e SC) e Sudeste (SP e MG) dão o maior retorno, principalmente em Informática (SC lidera com R$ 6,43 milhões só nessa categoria).
   - **O que fazer:** Colocar a maior parte da verba de anúncios em PR, SC, SP e MG, e fazer promoções de frete grátis em estados que compram menos, como o Rio Grande do Sul (RS), para atrair clientes.

4. **Criar promoções nos meses mais fracos do ano:**
   - As vendas sobem muito no fim do ano (dezembro bateu R$ 4,16 milhões), mas caem bastante no começo do ano (fevereiro caiu para R$ 2,36 milhões).
   - **O que fazer:** Fazer campanhas fora de época nos meses fracos (fevereiro, junho e setembro), como "Semana do Consumidor" ou "Volta às Aulas / Home Office".

5. **Treinar a equipe usando o jeito dos melhores vendedores:**
   - Vendedores como Carlos Eduardo (R$ 8,11 milhões e ticket médio de R$ 4.848,85) e Fernanda Alves (R$ 7,84 milhões) vendem mais porque fecham pedidos de maior valor.
   - **O que fazer:** Usar o exemplo deles para treinar o resto da equipe a oferecer produtos mais caros (como Notebooks e Smart TVs) junto com os itens simples.

## Ferramentas Usadas
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---
Desenvolvido por **Marcelo Sousa de Mendonça**
