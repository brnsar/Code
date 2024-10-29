# Análise de Logs Web Apache Spark 

## Descrição do Projeto
Este projeto realiza uma análise de logs usando Apache Spark no Databricks, com o objetivo de análisar informações dos registros de acesso de uma aplicação. Ele organiza e processa logs para identificar os maiores IPs de acesso, endpoints mais acessados, quantidade de IPs únicos, contagem de dias representados, análise de tamanho de resposta e análise de erros HTTP.


## Acesso ao Projeto
O projeto está disponível no GitHub. Para acessá-lo, siga o link: ([https://github.com/brnsar/Code]).
Baixe o arquivo intitulado Projeto.dbc e suba ele no Databricks (Vá em import e selecione o arquivo baixado).

### Estrutura do Repositório
- **Projeto.dbc**: O notebook Databricks que contém o código e os passos de análise.
- **README.md**: Este arquivo de documentação.

## Pré-requisitos
- **Conta no Databricks**: Você precisará de uma conta Databricks (a utilizada no projeto foi a Community Edition).
- **Python e Spark**: O código foi desenvolvido utilizando Python(3.9.19) e Spark(3.3.2).

## Instruções para Uso

### 1. Acesse o Notebook
- Baixe o repositório para seu ambiente local.
- Abra o notebook 
- Execute a primeira e segunda célula obrigatoriamente para o arquivo funcionar corretamente nas próximas células (É recomendado que utilize o "Run all" logo de primeira para não impactar a criação do DataFrame unificado que estará disponivel nas próximas células).
- As células de 8 a 10 são para a criação e visualização da tabela no DeltaLake, sendo a 8 para criação do DataFrame unificado, a 9 para salvar o DataFrame Unificado no Delta Lake e a 10 criar uma tabela para consulta.
- As células 11 e 12 representam um exemplo prático de como a tabela criada anteriormente pode ser utilizada como consulta e visualização dos dados salvos no DeltaLake.
- No código, há títulos e comentários facilitando seu manuseio.

## Escolha das tecnologias
Para o desenvolvimento desse projeto de análise de logs, foram utilizadas tecnologias como:

### 1. Databricks
Plataforma para análise unificada que combina o requisito obrigatório do projeto, como o APache Spark, com escalabilidade da nuvem. O DataBricks permite o processamento de grande volume de dados e oferece uma interface amigavel ao usuário. Outro ponto importante para sua escolha ao invés do Docker, é que o DataBricks é uma das ferramenas mais utilizadas no ambiente de trabalho atual.

### 2. Apache Spark
Poderoso mecanismo de processamento de dados para realizar a análise em larga escala. Foi utilizado para ler, processar e analisar os logs de forma rápida e eficiente.

### 3. Python
A linguagem de programação escolhida, oferece uma sintaxe clara e uma vasta biblioteca de recursos, o que failita a manipulação de dados e a integração com o Apache Spark.

## Contato
Para mais informações ou perguntas, entre em contato:
- **Nome**: [Bruna Soares]
- **Email**: [brnsar6@gmail.com]

