https://fullstackcode.dev/2022/07/09/run-oracle-database-with-docker/

## Subir o container
```
docker-compose up

# Para rodar em background usar o parâmetro -d

docker-compose up -d

```

## Acessar o bash do container

```
docker exec -ti ID_Do_Container_No_Docker bash
```


## Remover todos os dados salvos no volume

```
docker compose down --volume
```