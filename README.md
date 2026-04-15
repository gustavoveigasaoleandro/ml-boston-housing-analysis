# ml-boston-housing-analysis

Projeto de estudo em machine learning aplicado ao conjunto de dados Boston Housing. O objetivo e explorar um fluxo basico de analise tabular para entender variaveis habitacionais e preparar experimentos de regressao.

## Conteudo

- `boston_housing_analysis.ipynb`: notebook principal de analise e modelagem.
- `housing.csv`: base tabular usada no estudo.
- `.gitignore`: exclusoes de cache, ambiente virtual e artefatos locais.

## Objetivo do Estudo

Este repositorio demonstra um fluxo introdutorio para problemas supervisionados de regressao:

- carregamento e inspecao de dados tabulares;
- analise exploratoria de variaveis;
- preparacao de features;
- treino e avaliacao de modelos preditivos;
- registro do raciocinio em notebook.

## Base de Dados

A base `housing.csv` contem variaveis habitacionais e socioeconomicas usadas para estimar valores relacionados a moradias. O dataset foi mantido no repositorio por ser pequeno e necessario para reproduzir o notebook.

## Como Executar

1. Crie e ative um ambiente Python.
2. Instale as bibliotecas usadas no notebook, como `pandas`, `numpy`, `matplotlib`, `seaborn` e `scikit-learn`.
3. Abra o notebook:

```bash
jupyter notebook boston_housing_analysis.ipynb
```

## Cuidados

O repositorio tem finalidade educacional. Antes de usar os resultados em qualquer contexto real, revise premissas, metricas, vieses do dataset e adequacao do modelo.
