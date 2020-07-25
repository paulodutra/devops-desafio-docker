# Desafio Docker

## Parte 1 - Docker + Laravel
Este projeto possui os seguintes containers:
- app-desafio 
- db-desafio (porta 33336 da maquina para a porta 3306 do container)
- nginx-desafio (porta 8088 da maquina para a porta 80 do container)
- redis-desafio (porta 6379 da maquina para a porta 6379 do container)


# Parte 2 - Desafio golang
Como parte do desafio temos uma imagem que utiliza como base golang:1.14-alpine dentro da pasta **docker-image-golang** 

Para buildar e executar a imagem go lang:

```
docker build -t paulodutra/codeeducation .
docker run paulodutra/codeeducation
```

<a href="https://hub.docker.com/repository/docker/paulodutra/codeeducation" target="__blank">Imagem golang Docker Hub</a>

