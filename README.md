## Análise de Performance e Recomendação de Venda de Lojas

Este projeto realiza uma análise exploratória e visualização de dados para avaliar a performance de quatro lojas distintas, com o objetivo de identificar a unidade com o menor desempenho e fundamentar uma recomendação estratégica.

## Conjunto de Dados

Os dados utilizados neste projeto foram obtidos dos seguintes URLs:

*   Loja 1: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv`
*   Loja 2: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv`
*   Loja 3: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv`
*   Loja 4: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv`

Cada arquivo CSV contém dados de vendas e informações relacionadas para uma loja específica.

## Análises Realizadas

O projeto conduz as seguintes análises:

1.  **Análise do Faturamento:** Cálculo e comparação do faturamento total de cada loja e do faturamento total consolidado. Visualização através de gráfico de barras.
2.  **Vendas por Categoria:** Análise das vendas agrupadas por categoria de produto para cada loja e para o total das lojas. Visualização através de gráficos de linha e um gráfico de barras agrupadas para comparação entre as lojas.
3.  **Média de Avaliação das Lojas:** Cálculo e comparação da média de avaliação de compra para cada loja. Visualização através de gráfico de área.
4.  **Produtos Mais e Menos Vendidos:** Identificação dos produtos com maior e menor venda (baseado no preço) em cada loja. Visualização opcional dos top N produtos mais e menos vendidos por loja através de gráficos de barras.
5.  **Frete Médio por Loja:** Cálculo e comparação da média de frete para cada loja. Visualização através de gráfico de pizza para mostrar a distribuição percentual do frete médio.

## Ferramentas e Bibliotecas

*   Python
*   Pandas: Para manipulação e análise dos dados.
*   Matplotlib: Para criação das visualizações.
*   Google Colaboratory ou Jupyter Notebooks: Ambiente de execução do código.

## Estrutura do Código

O código está organizado em células (em um notebook Jupyter/Colab) que realizam as seguintes etapas:

1.  Importação das bibliotecas necessárias.
2.  Carregamento dos dados dos arquivos CSV para DataFrames Pandas.
3.  Realização das análises e cálculos para cada indicador.
4.  Geração dos gráficos para visualização dos resultados.
5.  Geração de um relatório textual resumindo as descobertas e a recomendação.

## Relatório e Recomendação

Ao final da análise, um relatório detalhado é gerado, apresentando as conclusões sobre o desempenho de cada loja com base nos indicadores analisados. A Loja 4 foi identificada como a unidade com o menor desempenho geral em termos de faturamento, vendas por categoria, avaliação do cliente e vendas de produtos de destaque.

**Recomendação Principal:**

Com base nos dados analisados, a recomendação é **considerar a venda da Loja 4** devido ao seu desempenho inferior em múltiplos indicadores-chave. Os recursos e esforços poderiam ser realocados para fortalecer as outras unidades mais rentáveis.

Para detalhes completos da análise e do raciocínio por trás da recomendação, consulte o código e as saídas geradas.

## Como Executar

Para executar este projeto:

1.  Abra o notebook em um ambiente Google Colaboratory ou Jupyter Notebook.
2.  Certifique-se de ter as bibliotecas `pandas` e `matplotlib` instaladas. Se não estiverem, utilize `!pip install pandas matplotlib` em uma célula do notebook.
3.  Execute as células do notebook sequencialmente.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorar a análise, adicionar novas visualizações ou refinar o código.
