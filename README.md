# Análise de Dados de Experimentos Biológicos

Este repositório contém uma análise exploratória de um conjunto de dados de experimentos biológicos, com o uso das bibliotecas `pandas`, `seaborn`, e `matplotlib`. A análise foi realizada no Google Colab e visa explorar os principais compostos, tratamentos e comportamentos dentro do conjunto de dados, bem como suas correlações.

## Descrição do Projeto

Neste projeto, realizamos a importação e exploração de um conjunto de dados de experimentos biológicos, disponível no GitHub. Aplicamos técnicas de visualização de dados para obter insights, como distribuição dos tratamentos, doses e compostos. Também exploramos correlações entre diferentes variáveis genéticas (`g-0`, `g-700`, etc.) e geramos gráficos para entender melhor a relação entre as variáveis.

### Principais Tópicos da Análise:
- Carregamento e limpeza de dados
- Distribuição dos tratamentos, doses e compostos
- Visualização com gráficos de barra e scatterplots
- Análise de correlação entre variáveis
- Geração de heatmaps para correlações

## Bibliotecas Utilizadas

A análise utilizou as seguintes bibliotecas:

- `pandas`: Para manipulação de dados
- `seaborn`: Para visualização de dados
- `matplotlib`: Para visualizações adicionais
- `numpy`: Para operações numéricas

## Dados

Os dados utilizados para a análise estão disponíveis no repositório da [Alura Cursos](https://github.com/alura-cursos/imersaodados3/blob/main/dados/dados_experimentos.zip?raw=true), e foram carregados diretamente através da URL no formato zip.

```python
import pandas as pd

url_dados = "https://github.com/alura-cursos/imersaodados3/blob/main/dados/dados_experimentos.zip?raw=true"
dados = pd.read_csv(url_dados, compression='zip')
