# NLP_Classificacao
# Classificação de tweets

## Autores: Michele Vanessa Sercundes Nunes e Krsna Murari de Albuquerque Rodrigues 

## OBJETIVO:

O objetivo do projeto é fazer uma análise de sentimentos em tweets, onde os tweets foram pré-processados e os dados foram divididos em conjuntos de treino, validação e teste. Posteriormente, vários algoritmos de classificação foram explorados para modelagem, incluindo Naive Bayes, SVC (Support Vector Classifier), Gaussian Naive Bayes e Random Forest.

## Detalhes do projeto:

### 1.Limpeza e Pré-processamento dos Dados:

Utilização de técnicas de processamento de linguagem natural (NLP) para limpar e preparar os dados dos tweets, incluindo remoção de menções, hashtags, URLs, caracteres especiais e números, além de conversão para minúsculas e lematização.

### 2.Vetorização dos Textos:

Os tweets foram vetorizados utilizando a técnica TF-IDF (Term Frequency-Inverse Document Frequency), que converte texto em vetores numéricos para análise por algoritmos de aprendizado de máquina.

### 3.Seleção de Algoritmos de Predição:

Foram selecionados quatro algoritmos de predição para análise de sentimento nos tweets: Naive Bayes, Support Vector Classifier (SVC), Gaussian Naive Bayes e Random Forest.

### 4.Otimização de Hiperparâmetros:

Utilização da biblioteca Optuna para otimizar os hiperparâmetros dos modelos de predição, visando melhorar suas performances. 

### 5.Avaliação dos Modelos:

Avaliação dos modelos utilizando métricas Accuracy (Acurácia): O modelo apresentou uma acurácia de aproximadamente 17.64%, o que indica que apenas 17.64% das previsões feitas pelo modelo estavam corretas em relação às classificações reais.

Hamming Loss: O Hamming Loss é uma métrica que mede a fração de rótulos incorretamente previstos para um conjunto de amostras. Neste caso, o Hamming Loss foi de aproximadamente 17.69%, o que significa que, em média, cada rótulo foi previsto incorretamente em cerca de 17.69% das amostras.

### 6.Resultados e Insights:

Apesar do modelo Gaussian Naive Bayes ter apresentado o melhor desempenho na métrica de otimização de hiperparâmetros, suas métricas de avaliação, Tanto a acurácia quanto o Hamming Loss estão abaixo do esperado, o que sugere que o modelo pode não estar capturando adequadamente os padrões nos dados ou que os dados podem não ser representativos o suficiente para este tipo de tarefa.

Insights adicionais podem ser obtidos investigando a distribuição das classes nos dados, explorando diferentes estratégias de pré-processamento de texto e considerando a possibilidade de utilizar modelos mais complexos ou técnicas avançadas de aprendizado de máquina para melhorar o desempenho da classificação.




