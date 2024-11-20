# 💸 Análise e Previsão de Dados de Gorjetas

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

## Metodologia:

O Projeto será desenvolvido utilizando a metodologia CRISP-DM, seguindo os seguintes passos:

1. Entendimento de negócio
2. Entendimento de dados
3. Preparação dos dados
4. Modelagem


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
