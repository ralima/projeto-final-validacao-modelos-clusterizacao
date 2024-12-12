# Projeto Final - Algoritmos de Clusterização

Este repositório contém o código e as análises realizadas para o projeto final da disciplina **Algoritmos de Inteligência Artificial para Clusterização** da pós-graduação em Inteligência Artificial do **Instituto Infnet**.

## Estrutura do Repositório

- `projeto_final_clusterizacao.ipynb`: Notebook principal com todo o código, análises e visualizações realizadas no projeto.
- `requirements.txt`: Lista de dependências e pacotes necessários para rodar o projeto.
- `README.md`: Descrição do projeto e instruções para execução.
- Dados utilizados:
  - `Country-data.csv`: Dataset utilizado no projeto (disponível no [Kaggle](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)).

## Descrição do Projeto

O projeto abrange:

1. **Instalação e Configuração do Ambiente**
   - Criação de um ambiente virtual usando `virtualenv` ou `conda`.
   - Instalação das dependências via `requirements.txt`.

2. **Análise dos Dados e Pré-processamento**
   - Descrição e entendimento da base de dados.
   - Escalonamento e tratamento de outliers.

3. **Clusterização**
   - Aplicação dos algoritmos de **K-Means** e **Clusterização Hierárquica**.
   - Adaptação do K-Means para identificar medóides.
   - Análise dos clusters formados e comparação entre métodos.

4. **Análises e Visualizações**
   - Gráficos explicativos para faixas dinâmicas das variáveis e distribuição dos clusters.
   - Interpretação dos resultados dos algoritmos.

5. **Comparação de Métodos**
   - Comparação entre **K-Means** e **Clusterização Hierárquica**.
   - Explicação de vantagens e desvantagens de cada método, especialmente com relação a outliers.

6. **DBScan**
   - Embora esteja fora do escopo inicial deste trabalho, inclui alguns experimentos preliminares com o algoritmo **DBScan**.

## Detalhes do Dataset

O dataset utilizado é o [Country Data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data), que contém informações socioeconômicas e de saúde de diversos países. Abaixo, uma breve descrição dos campos:

- **country**: Nome do país.
- **child_mort**: Taxa de mortalidade infantil por 1.000 nascimentos.
- **exports**: Exportações como porcentagem do PIB.
- **health**: Gastos com saúde como porcentagem do PIB.
- **imports**: Importações como porcentagem do PIB.
- **income**: Renda per capita.
- **inflation**: Taxa de inflação anual.
- **life_expec**: Expectativa de vida ao nascer.
- **total_fer**: Taxa de fertilidade total.
- **gdpp**: Produto Interno Bruto per capita.

## Requisitos

- **Python 3.9 ou superior**
- **Jupyter Notebook** ou **Jupyter Lab**
- Pacotes listados no arquivo `requirements.txt`
