# Perfil-do-turista-brasileiro-por-estado
Clusterização do perfil de turistas brasileiros com K-Means, utilizando dados do IBGE para identificar diferentes perfis de viagem e características socioeconômicas.

### **Objetivo**

Este estudo tem como objetivo identificar diferentes perfis de turistas brasileiros por Unidades da Federação por meio de técnicas de aprendizado não supervisionado, utilizando dados secundários da Pesquisa Nacional por Amostra de Domicílios Contínua (PNAD Contínua) do Instituto Brasileiro de Geografia e Estatística (IBGE), referentes aos anos de 2020, 2021, 2023 e 2024, considerando as 27 Unidades da Federação.

### **Metodologia**

As variáveis analisadas abrangem finalidade da viagem, tipo de hospedagem, meio de transporte e gasto médio por faixa de renda. 

Em Python foi realizado o tratamento dos dados pelo método Knowledge Discovery in Databases (KDD) com a integração de cinco bases de dados distintas sendo conectadas pelo ano de referência e UF, normalização de dados por proporção e utilizando a padronização z-core com o StandardScaler, posteriormente, aplicou-se o algoritmo K-means, com o número de clusters definido em três, definido pelo método do cotovelo. 

### **ANOVA**

- A Análise de Variância (ANOVA) foi utilizada para identificar as variáveis com maior poder discriminante entre os grupos.

No teste da estatística F o p-valor apresentou valores abaixo de 0,05  rejeitando a hipótese nula, indicando significância nas variáveis de análise. A análise de variância (ANOVA) apontou que as três variáveis com maior poder discriminante entre os grupos foram o uso de carro particular, outros meios de hospedagem e pelo uso de van. 

No geral, o gasto com viagens foi a variável de menor poder discriminante entre os clusters, o que sugere que o comportamento de viagem não é determinado exclusivamente pela capacidade de gasto

