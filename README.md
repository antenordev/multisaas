# multisite

Controles multisite

Subir container em background

```
docker-composer up -d --build
```

Descer container em background

```
docker-composer down -d --build
```

Subir container com terminal integrado

```
docker-composer up --build
```

Descer container com terminal integrado

```
docker-composer down --build
```

Estatísticas de Consumo de Containers

```
docker stats
```

Parar Container

```
docker stop CONTAINER_NAME
```

Apagar Container

```
docker rm -f CONTAINER_NAME
```

Apagar Imagem

```
docker rmi -f IMAGE_NAME
```

Parar Todos os containers

```
docker stop $(docker ps -a -q)
```

Deletar Todos os containers

```
docker rm -f $(docker ps -a -q)
```

Deletar Todas as Imagens (ATENÇÃO!)

```
docker system prune -f -a
```

Rodar comando de permissão de edição de templates e plugins

```
sudo chmod 777 -R services/app/wp-content
```

Hospedar aplicação em:

```
services/app/wp-content/themes
```
