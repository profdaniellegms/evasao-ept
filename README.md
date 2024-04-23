# Estudo da evasão escolar nos cursos do eixo de Informação e Comunicação da RFEPCT

## Objetivo

Identificar e prever os fatores de impacto na evasão escolar de alunos da Rede Federal de Educação Profissional, Científica e Tecnológica (RFEPCT) matriculados nos cursos do eixo tecnológico Informação e Comunicação, através de um Modelo Preditivo de Classificação Binária obtido por um algoritmo de Aprendizado de Máquina Supervisionado.

## Fontes de dados

Este trabalho utiliza os seguintes conjuntos de dados da Plataforma Nilo Peçanha, ambiente virtual mantido pela Secretaria de Educação Profissional e Tecnológica do Ministério da Educação (SETEC/MEC) para cálculo e disseminação das estatísticas oficiais da RFEPCT.

- Microdados de Matrículas (2018 a 2021)
- Microdados de Eficiência Acadêmica (2018 a 2021)
  
Ambos os conjuntos de dados foram obtidos no Portal de Dados Abertos do Governo Federal: dados.gov.br

## Metodologia

As etapas deste trabalho são aquelas definidas por Fayyad et al. (1996), adaptadas por Ltifi et al. (2013):

- ACESSO aos conjuntos de dados
- SELEÇÃO dos dados de interesse, ou dados alvo
- PRÉ-PROCESSAMENTO dos dados de interesse, incluindo as etapas de LIMPEZA e TRANSFORMAÇÃO, nesta ordem
- MINERAÇÃO dos dados limpos e transformados para extração de padrões com modelos preditivos de aprendizado de máquina
- AVALIAÇÃO e escolha do modelo preditivo de melhor desempenho

O portal contém conjuntos de dados de anos anteriores a 2018, porém as informações encontram-se incompletas e noutro padrão de formatação, de modo que estes conjuntos de dados foram desprezados neste trabalho.

## Algoritmos testados

- SVM (Máquinas de Vetores de Suporte)
- KNN (K Vizinhos mais Próximos)
- Regressão Logística
- Árvores de Decisão
- MLP (Perceptron Multicamadas)

## Métricas de Avaliação

Acurácia, Matriz de Confusão e Curva ROC

## Ferramentas

Linguagem Python: Jupyter Notebook, Numpy, iPython, Sci-kit Learn, Sci-Py, Pandas, Matplotlib

