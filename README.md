# Boston Housing Dataset

Projeto acadêmico com análise exploratória e manipulação do conjunto de dados Boston Housing em notebook Jupyter.

## Conteúdo

- `boston_housing_analysis.ipynb`: notebook principal do exercício.
- `housing.csv`: base de dados usada pelo notebook.

## Objetivo

Explorar o dataset Boston Housing, entender suas variáveis e executar o fluxo analítico solicitado na atividade.

## Requisitos

- Python 3.10+
- Jupyter Notebook ou JupyterLab
- `numpy`
- `pandas`

## Como executar

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter numpy pandas
jupyter notebook boston_housing_analysis.ipynb
```

## Observações

- O notebook espera encontrar o arquivo `housing.csv` no mesmo diretório.
- O dataset contém 14 colunas clássicas do problema de regressão de preços de imóveis em Boston.
