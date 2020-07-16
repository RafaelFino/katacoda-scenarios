# Vamos entender nosso ambiente
Veja a nossa estrutura de diretórios:
```
cd ~/learnops
exa -T
```{{execute}}

## Vamos começar com o nosso código na pasta cmd/dev-01 e fazer o execício de trocar o pneu do carro?*

Deixei um estrutura simples para podermos começar a colocar a mão na massa

## Para "buildar" nosso código
Entre na pasta do projeto (learnops) e digite

```
make dev-01
```{{execute}}

Se tudo estiver certo, na pasta learnops/bin foi criado um executável chamado *dev-01*, você pode tentar executa-lo para ver o resultado

```
bin/dev-01
```{{execute}}

## Para executar nosso código

Podemos executar o código sem precisar gerar um binário:
```
go run cmd/dev-01/main.go
```{{execute}}

Agora vamos alterar esse código para resolver o nosso problema! 