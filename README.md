# Challenge ONE Data Science - Alura Store

Este projeto faz parte do **Challenge ONE Data Science** da Alura e tem como objetivo analisar dados de vendas de uma loja fictícia chamada **Alura Store**. O notebook contém diversas análises e visualizações para extrair insights sobre o desempenho das lojas, categorias de produtos, avaliações dos clientes e custos de frete.

## Estrutura do Projeto

O projeto está estruturado em um único notebook (`AluraStoreBr.ipynb`), que realiza as seguintes etapas:

### 1. Importação dos Dados
Os dados de vendas são importados diretamente de arquivos CSV hospedados no GitHub. Cada loja possui um arquivo separado:
- Loja 1: `loja_1.csv`
- Loja 2: `loja_2.csv`
- Loja 3: `loja_3.csv`
- Loja 4: `loja_4.csv`

### 2. Análises Realizadas

#### **Faturamento**
- Cálculo do faturamento total de cada loja.
- Comparação do faturamento entre as lojas.

#### **Vendas por Categoria**
- Análise da quantidade de produtos vendidos por categoria em cada loja.
- Criação de uma tabela dinâmica para visualizar as vendas por categoria.

#### **Média de Avaliação**
- Cálculo da média de avaliação dos clientes para cada loja.

#### **Produtos Mais e Menos Vendidos**
- Identificação dos produtos mais vendidos e menos vendidos em cada loja.

#### **Frete Médio**
- Cálculo do custo médio de frete por loja.
- Comparação percentual do custo de frete entre as lojas.

### 3. Visualizações
- Gráfico de barras e linhas para comparar o faturamento e a satisfação dos clientes por loja.
- Gráfico de pizza para mostrar a distribuição de categorias de produtos na loja com maior faturamento.
- Gráfico de dispersão para analisar a relação entre preço, custo de frete e avaliação dos clientes.

## Tecnologias Utilizadas
- **Python**: Linguagem principal para análise de dados.
- **Pandas**: Manipulação e análise de dados.
- **Matplotlib** e **Seaborn**: Criação de gráficos e visualizações.
- **Jupyter Notebook**: Ambiente interativo para desenvolvimento e execução do código.

## Como Executar o Projeto
1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as dependências necessárias:
   ```bash
   pip install pandas matplotlib seaborn
3.Abra o arquivo AluraStoreBr.ipynb em um ambiente Jupyter Notebook ou similar.
4.Execute as células sequencialmente para reproduzir as análises e visualizações.

Licença
Este projeto está licenciado sob a MIT License.

Autor
Este projeto foi desenvolvido como parte do Challenge ONE Data Science por David Barcellos Cardoso.