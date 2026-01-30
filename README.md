Análise e Precificação de Diamantes com Machine Learning
Sobre o projeto

Este projeto aplica técnicas de Ciência de Dados e Machine Learning para resolver um problema real de negócio: precificação, segmentação e classificação de diamantes.

A proposta é transformar dados brutos em inteligência analítica para apoiar decisões comerciais, reduzir subjetividade humana e padronizar avaliações.

O projeto foi desenvolvido como parte do meu portfólio em Ciência de Dados, com foco em boas práticas de modelagem, validação estatística e pipelines reprodutíveis 

Projeto_Diamante

Objetivos

O projeto busca responder três perguntas principais:

Quanto um diamante deveria custar?
 Modelo de regressão para estimar preço

Quais perfis de diamantes existem?
 Modelo de clusterização para segmentação

Qual a qualidade do corte do diamante?
 Modelo de classificação

 Dataset

O dataset contém características físicas e qualitativas dos diamantes, incluindo:

Carat (peso)

Dimensões (X, Y, Z)

Depth e Table

Cor (Color)

Pureza (Clarity)

Corte (Cut)

Preço (Price)

Essas variáveis permitem análises preditivas e exploratórias ricas 

Projeto_Diamante


 Modelos Desenvolvidos
1️ Modelo de Regressão — Estimativa de Preço
 Técnicas utilizadas

StandardScaler

One-Hot Encoding

Pipeline com Scikit-Learn

Validação cruzada

Análise de resíduos

 Resultados

R² acima de 0.99 nos conjuntos de treino, validação e teste

Erros residuais baixos e distribuídos de forma aproximadamente simétrica

Forte capacidade de generalização

 O modelo consegue explicar mais de 99% da variância dos preços 

Projeto_Diamante

2️ Modelo de Clusterização — Segmentação de Diamantes
 Técnicas utilizadas

K-Means

Padronização dos dados

Método do Cotovelo

Método da Silhueta

Discretização

 Principais insights

Foram identificados grupos naturais de diamantes, como:

Diamantes menores e mais acessíveis

Diamantes médios com bom custo-benefício

Diamantes premium com alto carat e qualidade

Útil para estratégias de segmentação de mercado 

Projeto_Diamante

3️ Modelo de Classificação — Qualidade do Corte
 Técnicas utilizadas

Random Forest Classifier

Label Encoding

Pipelines de pré-processamento

Matrizes de confusão

Resultados

Acurácia de 100% em treino, validação e teste

Excelente separação entre classes

Alta estabilidade em dados de população

Indica forte capacidade de aprendizado dos padrões do dataset 

Projeto_Diamante

Tecnologias Utilizadas

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

Aplicações de Negócio

Este projeto pode ser aplicado para:

 Precificação automática
 Segmentação de mercado
 Apoio à decisão comercial
 Padronização de avaliações
 Redução de subjetividade humana

Aprendizados

Durante este projeto, foram reforçados conceitos de:

Pipelines de ML

Evitar data leakage

Validação estatística

Avaliação de modelos supervisionados e não supervisionados

Interpretação de resíduos

Storytelling com dados
