# Análise de Logs Web Apache Spark 

## Descrição do Projeto
Este projeto realiza uma análise de logs usando Apache Spark no Databricks, com o objetivo de análisar informações dos registros de acesso de uma aplicação. Ele organiza e processa logs para identificar os maiores IPs de acesso, endpoints mais acessados, quantidade de IPs únicos, contagem de dias representados, análise de tamanho de resposta e análise de erros HTTP.


## Acesso ao Projeto
O projeto está disponível no GitHub. Para acessá-lo, siga o link: (https://github.com/brnsar/Projeto---Code).
Baixe o arquivo intitulado Projeto.dbc e suba ele no Databricks.

### Estrutura do Repositório
- **Projeto.dbc**: O notebook Databricks que contém o código e os passos de análise.
- **README.md**: Este arquivo de documentação.

## Pré-requisitos
- **Conta no Databricks**: Você precisará de uma conta Databricks (a utilizada no projeto foi a Community Edition).
- **Python e Spark**: O código foi desenvolvido utilizando Python e Spark.

## Instruções para Uso

### 1. Acesse o Notebook
- Baixe o repositório para seu ambiente local.
- Abra o notebook 
- Execute a primeira e segunda célula obrigatoriamente e em seguida, poderá executar a célula desejada conforme a necesssidade, apertando no botão superior a esquerda como um 'play'.
- As celulas de 9 a 11 são para a criação de tabela no DeltaLake, sendo a 9 para criação do DataFrame unificado, a 10 para salvar o DataFrame Unificado no Delta Lake e a 11 criar uma tabela para consulta.
- No código, há títulos e comentários facilitando seu manuseio.

## Contato
Para mais informações ou perguntas, entre em contato:
- **Nome**: [Bruna Soares]
- **Email**: [brnsar6@gmail.com]
