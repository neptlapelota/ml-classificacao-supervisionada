# Resultados dos Testes

Este documento resume os testes executados no notebook de classificação supervisionada.

## Comparação de modelos

No exercício de classificação de problemas ortopédicos, foram avaliados três modelos principais:

| Modelo | Accuracy | Observação |
|---|---:|---|
| KNN | 0.73 | Modelo baseado em proximidade entre amostras |
| Decision Tree | 0.71 | Modelo interpretável por regras de decisão |
| Random Forest | 0.84 | Melhor desempenho entre os modelos testados |

## Melhor modelo observado

O **Random Forest** apresentou o melhor resultado, com aproximadamente **84% de acurácia** no conjunto de teste.

## Métricas utilizadas

Além da acurácia, o notebook também utiliza:

- precision;
- recall;
- f1-score;
- support;
- matriz de confusão.

## Observação sobre o exercício de diabetes

O notebook contém um exercício final com o dataset de diabetes do povo Pima. Para executar esse trecho, é necessário disponibilizar o arquivo `dataset_37_diabetes.arff` na pasta `data/` e ajustar o caminho de leitura no notebook.

## Consideração ética

Os exercícios com dados médicos possuem finalidade exclusivamente educacional. Os modelos não devem ser utilizados como ferramenta de diagnóstico real.
