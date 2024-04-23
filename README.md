# Evasão escolar na Rede Federal de Educação Profissional, Científica e Tecnológica (RFEPCT)

## Objetivo

Identificar os fatores de impacto na evasão escolar de alunos da RFEPCT matriculados nos cursos do eixo tecnológico Informação e Comunicação, estabelecido pelo Ministério da Educação (MEC) através de um Modelo Preditivo de Classificação Binária, obtido por um algoritmo de Aprendizado de Máquina Supervisionado.

## Fonte de dados

Este trabalho utiliza os seguintes conjuntos de dados da Plataforma Nilo Peçanha, ambiente virtual mantido pela Secretaria de Educação Profissional e Tecnológica (SETEC/MEC) para cálculo e disseminação das estatísticas oficiais da RFEPCT.

- Microdados de Matrículas (2018 a 2021)
- Microdados de Eficiência Acadêmica (2018 a 2021)
  
Ambos os conjuntos de dados foram obtidos através do Portal de Dados Abertos do Governo Federal: dados.gov.br

O portal contém conjuntos de dados de anos anteriores a 2018, porém as informações encontram-se incompletas e noutro padrão de formatação, de modo que estes conjuntos de dados foram desprezados neste trabalho.

## Algoritmos testados

- SVM (Máquinas de Vetores de Suporte)
- KNN (K Vizinhos mais Próximos)
- Regressão Logística
- Árvores de Decisão
- MLP (Perceptron Multicamadas)

## Ferramentas

Linguagem Python: Jupyter Notebook, Numpy, iPython, Sci-kit Learn, Sci-Py, Pandas, Matplotlib

