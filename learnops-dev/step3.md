# Vamos entender nosso ambiente

Nosso projeto tem essa estrutura:
.
├── bin
│  ├── chat-client
│  ├── chat-client.default-user.db
│  ├── chat-server
│  ├── chat-server.server.db
│  ├── data-creator
│  ├── db-api
│  ├── db-connect
│  ├── db-exec
│  ├── get-currency
│  ├── hello
│  └── simple-server
├── build
│  └── hello
│     ├── Analysis-00.toc
│     ├── base_library.zip
│     ├── COLLECT-00.toc
│     ├── EXE-00.toc
│     ├── hello
│     ├── localpycos
│     │  └── struct.pyo
│     ├── PKG-00.pkg
│     ├── PKG-00.toc
│     ├── PYZ-00.pyz
│     ├── PYZ-00.toc
│     ├── warn-hello.txt
│     └── xref-hello.html
├── cmd
│  ├── chat-client
│  │  └── main.go
│  ├── chat-server
│  │  └── main.go
│  ├── data-creator
│  │  └── main.go
│  ├── db-api
│  │  └── main.go
│  ├── db-connect
│  │  └── main.go
│  ├── db-exec
│  │  └── main.go
│  ├── dev-01
│  │  └── main.go
│  ├── get-currency
│  │  └── main.go
│  ├── hello
│  │  ├── hello.java
│  │  ├── hello.py
│  │  └── main.go
│  └── simple-server
│     └── main.go
├── daemon
│  ├── chat-server.service
│  ├── db-api.service
│  ├── nats-streaming.service
│  └── simple-server.service
├── etc
│  ├── chat-client-config.json
│  ├── chat-server-config.json
│  ├── create-db.sql
│  ├── db-config.json
│  ├── hello.html
│  ├── simple-server.conf
│  └── update.sql
├── go.mod
├── go.sum
├── internal
│  ├── chat
│  │  ├── common.go
│  │  ├── connection.go
│  │  ├── room.go
│  │  └── store.go
│  └── nats
├── LICENSE
├── main
├── makefile
└── scripts
   ├── content.txt
   ├── get-docker.sh
   ├── get-golang.sh
   ├── get-nats.sh
   ├── install-repo.sh
   ├── rhel-prepare.sh
   └── sysmon.sh

*Vamos começar com o nosso código na pasta cmd/dev-01 e fazer o execício de trocar o pneu do carro?*

Deixei um estrutura simples para podermos começar a colocar a mão na massa

## Para "buildar" nosso código
Entre na pasta do projeto (learnops) e digite
'''
make dev-01
'''

Se tudo estiver certo, na pasta learnops/bin foi criado um executável chamado *dev-01*, você pode tentar executa-lo para ver o resultado

Agora vamos alterar esse código para resolver o nosso problema! 