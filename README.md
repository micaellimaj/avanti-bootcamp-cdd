# Análise de dados sobre Gorjetas de um Restaurante 🫰

<p align="center">
    <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeHU4MnI3YnU4Z3B0aW91c2tzb3hqYjA1dDRydjhoem41YTZyYXdxeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Rk8CZk8M7UHzG/giphy.webp" />
</p>

O Projeto trate-se de uma análise de dados coletados de um restaurante por um garçom durante alguns meses, com diversos atributos que podem ser utilizados para gerar análises descritivas e estatísticas, permitindo avaliar o desempenho do restaurante durante o período e com base nisso melhorar a tomada de decisão e identificar os pontos fortes e fracos , assim conforme o objetivo da instituição/pessoa é possível investir em uma abordagem que possa aumentar os lucros de mitigar prejuízos.

## Atributos do dataset:

| Coluna                  | Descrição                                                                 | 
|------------------------|--------------------------------------------------------------------------|
| **total_bill**        | Representa o valor total da conta em dólares. Esta coluna indica o valor gasto por um grupo em um restaurante.                               | 
| **tip**                |  Representa o valor da gorjeta deixada em dólares.. Corresponde à quantia adicional paga ao garçom ou garçonete pelo serviço prestado.                                       |   
| **sex**                |  Indica o sexo da pessoa que pagou a conta. Os valores possíveis são "Male" (Masculino) e "Female" (Feminino).                                         |  
| **smoker**                | Indica se o cliente é fumante ou não. Os valores possíveis são "Yes" (Sim, fumante) e "No" (Não, não fumante).                                         |
| **day**                |   Representa o dia da semana em que a refeição foi consumida. Os valores possíveis são "Thur" (Quinta), "Fri" (Sexta), "Sat" (Sábado) e "Sun" (Domingo).                                         |
| **time**                | Indica se a refeição foi consumida durante o "Lunch" (Almoço) ou "Dinner" (Jantar).                                       |  
| **size**                |  Refere-se ao número de pessoas que estavam presentes na refeição (o tamanho do grupo).                                     |  

## Metodologia

O Projeto será desenvolvido utilizando a metodologia CRISP-DM, seguindo os seguintes passos:

1. Entendimento de negócio
2. Entendimento de dados
3. Preparação dos dados
4. Modelagem


### Organização de diretórios


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
