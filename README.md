# Machine Learning - Classificação Supervisionada

Projeto educacional desenvolvido em Jupyter Notebook para estudo de **aprendizado supervisionado aplicado à classificação**.

O material trabalha conceitos de Machine Learning com Python, passando por etapas como:

- carregamento e exploração dos dados;
- separação entre treino e teste;
- transformação/escalonamento de atributos;
- treinamento de modelos de classificação;
- avaliação com métricas como accuracy, precision, recall, f1-score e matriz de confusão.

## Tecnologias utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn

## Modelos abordados

Durante o estudo, foram utilizados e comparados modelos como:

- LDA
- KNN
- Decision Tree
- Random Forest

## Resultados observados no notebook

Em um dos exercícios executados no notebook, voltado à classificação de problemas ortopédicos, os modelos apresentaram os seguintes resultados de acurácia no conjunto de teste:

| Modelo | Acurácia aproximada |
|---|---:|
| KNN | 73% |
| Decision Tree | 71% |
| Random Forest | 84% |

O **Random Forest** apresentou o melhor desempenho nessa comparação.

## Exercício com dados de diabetes

O notebook também contém um exercício educacional com o dataset de diabetes do povo Pima.

Observação: o bloco final do exercício espera o arquivo `dataset_37_diabetes.arff`. Para executar localmente, coloque esse arquivo dentro da pasta `data/` e ajuste o caminho no notebook para:

```python
data, meta = arff.loadarff('../data/dataset_37_diabetes.arff')
```

## Objetivo do projeto

O objetivo deste projeto é demonstrar prática em classificação supervisionada e avaliação de modelos, sem finalidade médica ou diagnóstica.

Este é um estudo educacional para consolidar conhecimentos em Machine Learning, análise de dados e interpretação de métricas.

## Estrutura do repositório

```text
ml-classificacao-supervisionada/
├── notebooks/
│   └── classificacao_supervisionada_diabetes.ipynb
├── data/
│   └── README.md
├── docs/
│   ├── RESULTADOS.md
│   └── LINKEDIN.md
├── requirements.txt
├── .gitignore
└── README.md
```

## Como executar

1. Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/ml-classificacao-supervisionada.git
cd ml-classificacao-supervisionada
```

2. Crie e ative um ambiente virtual:

```bash
python -m venv .venv
source .venv/bin/activate
```

No Windows:

```bash
.venv\Scripts\activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Abra o notebook:

```bash
jupyter notebook notebooks/classificacao_supervisionada_diabetes.ipynb
```

## Aviso

Este projeto tem finalidade exclusivamente educacional. Os modelos e resultados apresentados não devem ser utilizados para diagnóstico médico real.
