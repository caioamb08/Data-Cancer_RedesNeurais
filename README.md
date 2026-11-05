# Data Cancer — Parte 2: Redes Neurais Artificiais

Projeto de Machine Learning voltado à classificação de tumores de mama como benignos ou malignos, utilizando uma Rede Neural Artificial (MLP — Multi-Layer Perceptron).

Este repositório representa a **segunda etapa do projeto Data Cancer**, dando continuidade ao trabalho anterior, no qual explorei diferentes algoritmos de Machine Learning e técnicas de preparação e análise de dados.

**Projeto anterior:** [Data Cancer — Classificação com Machine Learning](https://github.com/caioamb08/Data-cancer)

---

## Objetivo do projeto

Dar continuidade ao estudo de classificação de tumores de mama, aprofundando os conhecimentos em redes neurais artificiais e explorando diferentes técnicas de preparação dos dados, treinamento e avaliação de modelos.

O objetivo também é documentar minha evolução prática em Python, Machine Learning e análise de dados, registrando os métodos e ferramentas estudados durante o desenvolvimento.

## Base de dados

Foi utilizado o conjunto de dados **Breast Cancer Wisconsin (Diagnostic)**, composto por informações numéricas extraídas de características de células mamárias.

- 569 registros;
- 30 características numéricas;
- Variável-alvo: diagnóstico do tumor;
- Classificação binária:
  - `0`: Maligno (M);
  - `1`: Benigno (B).

A tabela original foi incluída no repositório para permitir a consulta dos dados utilizados no projeto.

## Etapas desenvolvidas

Ao longo do notebook, foram exploradas diferentes etapas de um fluxo de Machine Learning:

1. **Importação e exploração dos dados:** leitura da base original, visualização das primeiras observações e análise da estrutura do DataFrame.
2. **Tratamento dos dados:** identificação e remoção de colunas desnecessárias, análise de valores ausentes e preparação da variável-alvo.
3. **Pré-processamento:** exploração de técnicas de transformação e preparação das variáveis, incluindo ferramentas como `OneHotEncoder` e `StandardScaler`.
4. **Exploração de técnicas adicionais:** utilização de ferramentas e métodos estudados durante o aprendizado, incluindo Instance Scanner.
5. **Divisão dos dados:** separação entre conjuntos de treinamento e teste.
6. **Rede Neural Artificial:** implementação de um modelo MLP utilizando o `MLPClassifier` da biblioteca Scikit-learn.
7. **Avaliação do modelo:** análise da acurácia, validação cruzada e matriz de confusão.

O notebook mantém também experimentos e etapas intermediárias, documentando diferentes técnicas estudadas durante o processo de aprendizado.

## Modelo de Rede Neural

Foi utilizado o algoritmo `MLPClassifier`, com a seguinte configuração:

- Arquitetura: duas camadas ocultas;
- Neurônios: 16 e 8;
- Função de ativação: ReLU;
- Otimizador: Adam;
- Número máximo de iterações: 1000.

## Resultados do experimento

Nos resultados registrados no notebook:

| Métrica | Resultado |
|---|---:|
| Acurácia no conjunto de teste | 97,66% |
| Acurácia média na validação cruzada | 97,71% |
| Classificações incorretas na matriz de confusão | 4 de 171 |

Esses resultados representam o desempenho observado durante o experimento atual. A avaliação ainda pode ser aprimorada com ajustes no processo de validação e pré-processamento.

## Tecnologias e bibliotecas

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Machine Learning
- Redes Neurais Artificiais (MLP)

## Aprendizados

Este projeto contribuiu para aprofundar meus conhecimentos em:

- Preparação e transformação de dados;
- Manipulação de DataFrames com Pandas;
- Pré-processamento de variáveis;
- Funcionamento de redes neurais artificiais;
- Treinamento e avaliação de modelos;
- Validação cruzada;
- Interpretação de métricas de classificação;
- Aplicação prática de ferramentas do Scikit-learn.

## Considerações finais

Esta segunda etapa representa a evolução do meu primeiro projeto de classificação de câncer de mama. Enquanto o trabalho anterior explorou e comparou diferentes algoritmos de Machine Learning, esta versão amplia os estudos com a implementação de uma Rede Neural Artificial.

Mais do que apresentar um resultado, o objetivo é demonstrar o processo de aprendizado, a experimentação com diferentes técnicas e a evolução na aplicação de conceitos de Ciência de Dados e Machine Learning.

**Observação:** projeto desenvolvido para fins educacionais e de estudo. Não deve ser utilizado para diagnóstico médico ou tomada de decisões clínicas.
