# Vamos preparar nosso ambiente?

## Preparando o terminal
Vamos baixar do nosso repositório um script para deixar nosso terminal mais legal
```
cd
curl https://raw.githubusercontent.com/RafaelFino/katacoda-scenarios/master/learnops-dev/scripts/prepare.sh | bash
zsh

```{{execute}}

## Baixando o código e preparando o ambiente
```
cd
git clone https://github.com/RafaelFino/katacoda-scenarios.git
katacoda-scenarios/learnops-dev/scripts/prepare.sh

```{{execute}}

## Para executar nosso server 

```
go run katacoda-scenarios/learnops-dev/car/server.go &
```{{execute}}

## Para executar nosso client

```
go run katacoda-scenarios/learnops-dev/car/client.go &
```{{execute}}

Agora vamos alterar esse código para resolver o nosso problema! 