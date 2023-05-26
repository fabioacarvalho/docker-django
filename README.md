# Docker and Django

_Para utilizar esse projeto você precisa ter o Docker instalado e configurado._

_O usuário e senha do postgreSQL será os mesmos que você definiu no arquivo .env_

## Iniciando o porjeto

Para iniciar o projeto basta fazer o __clone__ do repositório e rodar o comando.

```
git clone "https://LINK_DO_REPOSITORIO"
```

Feito isso dentro da pasta __dotenv_files__ crie um arquivo chamado __.env__ e adicionar os seguintes comandos:

``` 
SECRET_KEY="CHANGE-ME"
POSTGRES_DB="CHANGE-ME"
POSTGRES_USER="CHANGE-ME"
POSTGRES_PASSWORD="CHANGE-ME"
```
## Executando o projeto

Para executar o projeto basta rodar o comando:

``` 
docker-compose up --build 
```

Se quiser __forçar a recriação__ do container use o comando abaixo:

```
docker-compose up --build --force-recreate
```

## Comandos Extras

Se por acaso precisar __apagar um container__, você pode usar os seguintes comandos:

*Visualizar os container:*
```
docker ps -a
```

_Feito isso você pode verificar o __ID__ do container_

__Remover um container por ID:__
```
docker re ID_DO_CONTAIER
```