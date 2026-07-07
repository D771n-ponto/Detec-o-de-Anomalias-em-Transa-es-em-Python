# 🛡️ Detecção de Anomalias em Transações Financeiras com Python

Este repositório contém o projeto prático desenvolvido para a trilha de Dados, Cibersegurança e IA Generativa da DIO em parceria com o Bradesco. O objetivo principal é identificar transações fraudulentas usando técnicas avançadas de Machine Learning.

## 📊 O Desafio dos Dados
Em cenários reais de cibersegurança bancária, os dados de transações são altamente desbalanceados (o volume de fraudes é massivamente menor que o de operações legítimas). Treinar um modelo sem o devido tratamento faz com que a IA ignore as anomalias.

## 🛠️ Tecnologias e Técnicas Aplicadas
* **Linguagem:** Python
* **Tratamento de Dados Desbalanceados:** SMOTE (Synthetic Minority Over-sampling Technique) para balanceamento de classes.
* **Algoritmo de Classificação:** Random Forest Classifier do `scikit-learn`.
* **Métricas de Validação de Segurança:** Foco em maximizar o *Recall* para mitigar falsos negativos (fraudes não detectadas).

## 📁 Estrutura do Repositório
* `deteccao_anomalias.ipynb`: Código-fonte documentado com o pipeline de dados.
* `README.md`: Documentação explicativa do projeto.
