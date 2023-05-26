# Docker and Django

_Para utilizar esse projeto você precisa ter o Docker instalado e configurado._

_O usuário e senha do postgreSQL será os mesmos que você definiu no arquivo .env_

## Iniciando o porjeto

Para iniciar o projeto basta fazer o _clone_ do repositório e rodar o comando.

Feito isso dentro da pasta __dotenv_files__ crie um arquivo chamado _.env_ e adicionar os seguintes comandos:

``` 
SECRET_KEY="CHANGE-ME"
POSTGRES_DB="CHANGE-ME"
POSTGRES_USER="CHANGE-ME"
POSTGRES_PASSWORD="CHANGE-ME"
```
## Executando o projeto

Para executar o projeto basta rodar o comando:

``` docker-compose up --build ```