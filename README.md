# 💸 Análise e Predição de Dados de Gorjetas

![arquitetura do Projeto](data/raw/logo_tips.jpeg)

## 🔍 Introdução:

Este projeto tem como objetivo realizar uma análise aprofundada dos dados de gorjetas coletados por um garçom durante alguns meses. Os dados incluem informações sobre valor total da conta, valor da gorjeta deixada, sexo do cliente, dentre outros atributos listados logo adiante que influenciaram nas análises. Através de técnicas estatísticas e visualizações de dados, buscamos identificar padrões, tendências e correlações que possam influenciar o valor das gorjetas.

## 📜 Arquitetura do Projeto:

![arquitetura do Projeto](data/raw/arquiteturaprojeto.gif)

## 💡 Justificativa:

Em um mercado altamente competitivo, a capacidade de tomar decisões baseadas em dados é fundamental para o sucesso de um restaurante. A análise de gorjetas permite que o estabelecimento compreenda melhor o comportamento de seus clientes, identifique oportunidades de melhoria e aumente sua rentabilidade. Ao investir em uma análise aprofundada dos dados, o restaurante demonstra seu compromisso com a excelência operacional e a satisfação do cliente, garantindo um diferencial competitivo no mercado.


<p align="center">
    <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeHU4MnI3YnU4Z3B0aW91c2tzb3hqYjA1dDRydjhoem41YTZyYXdxeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Rk8CZk8M7UHzG/giphy.webp" />
</p>

## 📱 Tecnologias utilizadas:

<div align="center" style="display: inline_block">
<img align="center" alt="github" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img align="center" alt="vscode" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" /> 
<img align="center" src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="icon jupyter notebook">
<img align="center" src="https://img.shields.io/badge/Python-133DAB?style=for-the-badge&logo=python&logoColor=y1CC0C0" alt="icon python" >
    <img align="center" src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="icon pandas">
<img align="center" src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="icon numpy">
<img align="center" src="https://img.shields.io/badge/Matplotlib-0B2C4A?style=for-the-badge&logo=python&logoColor=white" alt="icon matplotlib">
<img align="center" src="https://img.shields.io/badge/Seaborn-4C4C4C?style=for-the-badge&logo=python&logoColor=white" alt="icon seaborn">
<img align="center" src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="icon scikit-learn">

    
</div>

## 📋 Atributos do dataset:

| Coluna                  | Descrição                                                                 | 
|------------------------|--------------------------------------------------------------------------|
| **total_bill**        | Representa o valor total da conta em dólares. Esta coluna indica o valor gasto por um grupo em um restaurante.                               | 
| **tip**                |  Representa o valor da gorjeta deixada em dólares.. Corresponde à quantia adicional paga ao garçom ou garçonete pelo serviço prestado.                                       |   
| **sex**                |  Indica o sexo da pessoa que pagou a conta. Os valores possíveis são "Male" (Masculino) e "Female" (Feminino).                                         |  
| **smoker**                | Indica se o cliente é fumante ou não. Os valores possíveis são "Yes" (Sim, fumante) e "No" (Não, não fumante).                                         |
| **day**                |   Representa o dia da semana em que a refeição foi consumida. Os valores possíveis são "Thur" (Quinta), "Fri" (Sexta), "Sat" (Sábado) e "Sun" (Domingo).                                         |
| **time**                | Indica se a refeição foi consumida durante o "Lunch" (Almoço) ou "Dinner" (Jantar).                                       |  
| **size**                |  Refere-se ao número de pessoas que estavam presentes na refeição (o tamanho do grupo).                                     |  

## 🏫 Metodologia:

O Projeto será desenvolvido utilizando a metodologia CRISP-DM, seguindo os seguintes passos:

1. Entendimento de negócio
2. Entendimento de dados
3. Preparação dos dados
4. Modelagem

## 📑 Etapas do Projeto:

Segue as etapas do projeto conforme os arquivos jupyter localizados na pasta notebooks.

### **0-tips-download**:

Este caderno é dedicado a etapa inicial do projeto, com o objetivo de entender a estrutura dos dados, fazendo a primeira leitura e criando um dicionário de dados. 

### **01-exploratory_data_analysis**:

Este caderno é dedicado à análise exploratória de dados (EDA), com o objetivo de entender a estrutura dos dados e obter insights iniciais. Ele está organizado em três etapas principais:

* **Descrição dos Dados**:
Nesta etapa, os dados são analisados quanto à sua estrutura, verificando a presença de valores faltantes, a distribuição das variáveis, e a criação de um dicionário de dados para facilitar a compreensão das informações.

* **Perguntas e Hipóteses**:
Aqui, são formuladas perguntas iniciais sobre os dados, seguidas de hipóteses baseadas nessas perguntas. Essas hipóteses serão verificadas na etapa final para avaliar sua validade.

* **Geração de Insights**:
Diversos gráficos e análises visuais são criados para responder às perguntas formuladas e testar as hipóteses. Com isso, buscamos confirmar ou refutar as hipóteses, gerando insights relevantes para o contexto do projeto.

### **02-comparative_analysis**:
Este caderno é voltado para a comparação de modelos de regressão e classificação, com o objetivo de identificar os melhores modelos para a previsão e classificação dos dados. O processo é dividido em várias etapas cruciais:

* **Tratamento e Transformação de Dados**:
    * A primeira etapa envolve a preparação dos dados para análise. Isso inclui a limpeza de dados faltantes, normalização, codificação de variáveis categóricas e outras transformações necessárias para garantir que os dados estejam prontos para alimentar os modelos.

* **Treinamento e Avaliação de Modelos**:
    * Nessa etapa, diferentes modelos de regressão (como LinearRegression, KNeighborsRegressor, SVR, DummyRegressor) e classificação (como LogisticRegression, KNeighborsClassifier) são treinados e avaliados. Para cada modelo, são calculadas métricas de desempenho como precisão, recall, F1-score, MAE, MSE e R², permitindo uma comparação detalhada de sua eficácia.

* **Comparação de Modelos** :
    * Através de uma análise comparativa, são avaliadas as forças e fraquezas de cada modelo com base nos resultados obtidos. Essa comparação abrange tanto as métricas de avaliação quanto as predições de cada modelo, considerando a adequação a diferentes tipos de dados e a capacidade de captura de padrões.

* **Geração de Insights**:
    * Por fim, são extraídos insights com base nas comparações entre os modelos. São apresentados gráficos e tabelas para ilustrar a performance de cada abordagem, destacando as melhores opções para o problema em questão. O objetivo é entender quais modelos têm o melhor desempenho em termos de generalização, precisão e adequação ao contexto dos dados.


## 🗂️ Organização de diretórios:


```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```

## 💯 Conclusão:

Este projeto demonstrou um fluxo completo de análise e modelagem de dados, passando por etapas fundamentais como pré-processamento, análise exploratória e comparação de diferentes modelos de regressão e Classificação. Ao final do processo, foi possível obter insights valiosos e selecionar o modelo mais adequado para a tarefa proposta.
