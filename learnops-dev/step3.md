# Vamos preparar nosso ambiente?

## Preparando o terminal
Vamos baixar do nosso repositório um script para deixar nosso terminal mais legal
```
cd
curl https://raw.githubusercontent.com/RafaelFino/katacoda-scenarios/master/learnops-dev/scripts/prepare.sh | bash
zsh

```{{execute}}

## Baixando o código
```
cd
curl https://raw.githubusercontent.com/RafaelFino/katacoda-scenarios/master/learnops-dev/car-client/main.go > car-client.go
curl https://raw.githubusercontent.com/RafaelFino/katacoda-scenarios/master/learnops-dev/car-server/main.go > car-server.go
zsh

```{{execute}}

## Para executar nosso server 

```
go run car-server.go &
```{{execute}}

## Para executar nosso client

```
go run car-server.go
```{{execute}}

Agora vamos alterar esse código para resolver o nosso problema! 