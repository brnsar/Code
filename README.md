# Análise de Logs Web Apache Spark 

## Descrição do Projeto
Este projeto realiza uma análise de logs usando Apache Spark no Databricks, com o objetivo de análisar informações dos registros de acesso de uma aplicação. Ele organiza e processa logs para identificar os maiores IPs de acesso, endpoints mais acessados, quantidade de IPs únicos, contagem de dias representados, análise de tamanho de resposta e análise de erros HTTP.


## Acesso ao Projeto
O projeto está disponível no GitHub. Para acessá-lo, siga o link: ([https://github.com/brnsar/Code]).
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
- Execute a primeira e segunda célula obrigatoriamente para o arquivo funcionar orretamente nas próximas células.
- As células de 8 a 10 são para a criação e visualização da tabela no DeltaLake, sendo a 8 para criação do DataFrame unificado, a 9 para salvar o DataFrame Unificado no Delta Lake e a 10 criar uma tabela para consulta.
- As células 11 e 12 representam um exemplo prático de como a tabela criada anteriormente pode ser utilizada como consulta e visualização dos dados salvos no DeltaLake.
- No código, há títulos e comentários facilitando seu manuseio.

## Contato
Para mais informações ou perguntas, entre em contato:
- **Nome**: [Bruna Soares]
- **Email**: [brnsar6@gmail.com]
