# Insurance ML Tasks

Este repositório contém um projeto desenvolvido para a companhia de seguros **Proteja Seu Amanhã**, com o objetivo de resolver desafios utilizando aprendizado de máquina e técnicas de proteção de dados. A proposta é explorar modelos preditivos, análise de clusters e ofuscação de informações pessoais.

## Objetivos do Projeto

1. **Encontrar clientes semelhantes a um determinado cliente**
   - Auxiliar as estratégias de marketing da empresa, identificando perfis similares.

2. **Predizer a probabilidade de um cliente receber um pagamento de seguro**
   - Avaliar modelos de classificação para prever se um cliente receberá pagamentos, superando modelos dummy.

3. **Predizer o número de pagamentos de seguro esperados**
   - Utilizar regressão linear para estimar a quantidade de pagamentos de seguro de novos clientes.

4. **Proteger os dados pessoais dos clientes**
   - Implementar um algoritmo de ofuscação de dados, mantendo a qualidade dos modelos preditivos.

## Etapas do Projeto

1. **Preparação e Análise de Dados**
   - Verificação e tratamento de valores ausentes, outliers e problemas no conjunto de dados.

2. **Desenvolvimento de Modelos**
   - Modelos preditivos para classificação e regressão.
   - Identificação de clientes semelhantes usando técnicas de clustering.

3. **Proteção de Dados**
   - Implementação de mascaramento de dados para proteger informações sensíveis, sem prejudicar a eficácia dos modelos.

4. **Avaliação e Conclusões**
   - Comparação de métricas como precisão, F1-score e desempenho geral.

## Descrição do Conjunto de Dados

O conjunto de dados inclui informações de clientes e seus históricos de pagamentos de seguro:

- **Features (Características):**
  - `sexo`
  - `idade`
  - `salário`
  - `número de familiares`
  
- **Target (Alvo):**
  - `número de pagamentos de seguro recebidos nos últimos 5 anos`

## Tecnologias Utilizadas

- **Linguagem:** Python  
- **Bibliotecas:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, etc.  
- **Técnicas:** Regressão Linear, Classificação, KNN, Ofuscação de Dados.
