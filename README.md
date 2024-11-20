# Análise e Previsão de Questões do ENEM por Disciplina

Este repositório contém uma análise detalhada das questões do ENEM nos últimos anos, com foco na classificação das questões por áreas de História e a previsão da quantidade de questões para 2024 utilizando modelos de séries temporais ARIMA.

## Objetivo

O objetivo deste projeto é analisar a distribuição de questões do ENEM por subtema ao longo dos anos, prever a quantidade de questões para 2025 e gerar insights sobre os temas mais abordados nas provas de História. A análise é realizada utilizando Python, Pandas, Matplotlib e modelos de séries temporais ARIMA.
É importante ressaltar que meu objetivo é trazer habilidades do universo de Análise de Dados para a Educação, permitindo que o docente tenha mais insumos para preparar suas aulas e conteúdos. Corro o risco de que este código seja interpretado como uma ferramenta que possa sustentar os argumentos de uma Educação Bancária, contudo não é essa a minha visão do processo educacional. Compreendo que o professor deve colaborar com a formação cidadã do alunato, mas também dialogar com tecnologias que permitam que nossos alunos alcancem seus objetivos pessoais e profissionais.

## Estrutura do Projeto

Este repositório contém os seguintes arquivos principais:

- **`notebooks/`**: Jupyter Notebooks contendo as etapas de análise e previsão.
- **`src/`**: Scripts Python para limpeza e transformação dos dados, bem como a modelagem ARIMA.
- **`images/`**: Pasta para armazenar imagens geradas (ex: gráficos e previsões).

## Etapas da Análise

A análise foi realizada em várias etapas:

### 1. **Classificação de Questões**
A primeira etapa foi classificar as questões por subtema. Para isso, aplicamos uma função de classificação que analisou o título das questões e as categorizou conforme subtemas da História, como "História Contemporânea", "História Medieval", etc.

### 2. **Limpeza e Preparação dos Dados**
Após a classificação, removemos entradas que continham subtemas irrelevantes (como "Geografia") e preparamos os dados para a análise.

### 3. **Análise Temporal**
A distribuição das questões ao longo dos anos foi analisada, observando as flutuações nas quantidades de questões por subtema, com a criação de gráficos.

### 4. **Previsão com ARIMA**
Foi utilizado o modelo ARIMA para prever a quantidade de questões para o ano de 2024. O ARIMA foi aplicado aos dados históricos para cada subtema de História, considerando que os dados eram estacionários.

## Dependências

Este projeto foi desenvolvido usando as seguintes bibliotecas Python:

- pandas
- numpy
- matplotlib
- statsmodels
- pmdarima (para auto-arima)

## Exemplo de resultados

O gráfico abaixo mostra a evolução das questões por subtema ao longo dos anos, destacando as flutuações nas quantidades de questões para cada tema:
