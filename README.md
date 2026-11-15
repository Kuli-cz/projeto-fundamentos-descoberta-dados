# Projeto Módulo 13 — Fundamentos da Descoberta de Dados

## Arquivos
- `M13_Projeto_Concluido.ipynb`: notebook com o código e as interpretações.
- `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv`: base original utilizada.
- `m13_boxplot_lacteos.png`: boxplot da categoria com maior desvio padrão.
- `m13_barras_desconto_categoria.png`: gráfico de barras do desconto médio por categoria.
- `m13_mapa_categoria_marca.png`: imagem estática de apoio do treemap.
- `m13_mapa_interativo_treemap.html`: versão interativa do treemap.

## Como executar
1. Baixe ou clone este repositório.
2. Instale as bibliotecas: `pip install pandas matplotlib plotly jupyter`.
3. Abra `M13_Projeto_Concluido.ipynb` no Jupyter Notebook ou JupyterLab.
4. Mantenha o CSV na mesma pasta do notebook e execute as células em ordem.

## Principais resultados
- A base contém 1.107 registros, 7 categorias e não apresenta valores ausentes.
- Em seis categorias, a média de `Preco_Normal` é maior que a mediana; em `comidas-preparadas`, é menor.
- `lacteos` tem o maior desvio padrão: aproximadamente 3.925,82 CLP.
- No boxplot de `lacteos`, o critério de 1,5 × IQR identifica 43 outliers entre 447 produtos.
- `congelados` apresenta o maior desconto médio: aproximadamente 154,03 CLP.

## Observação metodológica
O treemap agrupa por categoria e marca. A área representa a quantidade de produtos na combinação, e a cor representa o desconto médio. A coluna `Desconto` foi agregada incluindo os valores zero existentes na base.
