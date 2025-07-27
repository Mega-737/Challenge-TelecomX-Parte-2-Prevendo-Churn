# 💻 Projeto de Formação Estatística e Machine Learning G8 - ONEAlura

## 📊 *CHALLENGE TELECOM X: ANÁLISE DE EVASÃO DE CLIENTES - PARTE 2*

## 📌 Objetivo
O Desafio Telecom X parte 2 oferece uma oportunidade  para aplicar conhecimentos fundamentais de estatística, regressão linear 
e machine learning, além de habilidades essenciais de ciência de dados, em um cenário de negócio real. 
Missão: Desenvolver modelos preditivos capazes de prever quais clientes têm maior chance de cancelar seus serviços.

Projeto: `PREVENDO CHURN`

**Colocado em prática:**
- Pré-processamento de dados para Machine Learning
- Construção e avaliação de modelos preditivos
- Interpretação dos resultados e entrega de insights
- Comunicação técnica com foco estratégico

## 🧰 Tecnologias
Utilizou-se:
- Linguagem de programação: **Python**  
- Bibliotecas: **Pandas, Numpy, Matplotlib, Seaborn**  
- usou-se biblioteca: **https://scikit-learn.org/stable/**
- Plataforma gratuita baseada na nuvem que permite escrever e executar código Python: **Google Colab**  
- Plataforma baseada em nuvem para armazenamento, compartilhamento e colaboração: **GitHub**
- **Onehotencoder**, **Simpleimputer**

## 📂 Estrutura do Projeto
### 1. Extração dos Dados
- Importação dos dados da API da Telecom_X no GitHub, utilizando Python e convertendo-os para um DataFrame do Pandas, facilitando a manipulação. Os dados estão em formato JSON.
- Importação das bibliotecas necessárias.

### 2. Etapas
- Os dados foram extraídos com variáveis em inglês. Um dicionário no repositório ajuda na compreensão dos termos.
- Verificação e tratamento de inconsistências nos dados.
- Análise exploratória (EDA)
3. Modelagem com Regressão Logística, Random Forest e XGBoost
4. Avaliação dos modelos
5. Interpretação de resultados

### 3. Resultado da Análise  
| Fator | Risco associado |
|-------|------------------|
| Tipo de contrato mensal | Alta evasão |
| Faturamento total alto com poucos produtos | Alta evasão |
| Cliente individual (não familiar) | Maior probabilidade |
| Não uso de serviços adicionais (streaming, segurança, suporte técnico) | Associado à evasão |
| Clientes com menos de 1 ano de serviço | Alta taxa de churn |
| Contas com cobrança eletrônica e pagamento automático | Evasão acima da média |

### 4. Recomendações para redução da Evasão dos Clientes
1. Incentivar **planos anuais/trimestrais**.
2. Oferecer **pacotes de valor agregado**.
3. Campanhas de **retenção para clientes com alto faturamento**.
4. **Acompanhamento ativo nos primeiros 12 meses**.
5. Estratégias voltadas a **clientes individuais**.

### 5. Fonte dos Dados
- Banco de Dados extraído da plataforma do GitHub: [ingridcristh/challenge2-data-science](https://github.com/ingridcristh/challenge2-data-science)
- Acesso ao projeto no GitHub: https://github.com/Mega-737/Challenge-TelecomX-Parte-2-Prevendo-Churn.git

## ®️ Licença
Este projeto está sob a **<u>LICENÇA MIT</u>** 
