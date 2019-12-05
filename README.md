# c.rda (corda foundation)

Corda é um projeto DLT da empresa R3 e nasceu de um consórcio privado entre +70 (2015) bancos, mais tarde na v1.0 (2017) o projeto se torna open source.

# Corda Open vs Enterprise 

|Open|Enterprise|
|---|---|
|Sem suporte uso da comunidade|Suporte 24x7 equipe R3|
|garante até 25 TPS|garantem de 600 à 1K TPS|
|não garante interoperabilidade nativa com outra databases|garante interoperabilidade nativa com outra databases|
||fee por transação|

# Plataforma Corda

1. Rede Permissionada 
2. Privacidade e transações confidênciais
3. Não e criptomoeda
4. SmartContract

# Na Virtual Machine...

Abra um terminal novo:

```bash
# volte para seu home

# acesse o diretorio corda
cd ~/corda/tools/demobench/build/install/demobench/

# abrir o frontend
bin/demobench
```

![GitHub Logo](fig01.png)


```bash

   ______               __
  / ____/     _________/ /___ _
 / /     __  / ___/ __  / __ `/         I named my dog 'Six Miles' so I can tell
/ /___  /_/ / /  / /_/ / /_/ /          people I walk Six Miles every day.
\____/     /_/   \__,_/\__,_/

--- Corda Open Source 4.4-SNAPSHOT (76e0054) -------------------------------------------------------------


Logs can be found in                    : /home/aluno/demobench/20191205211638/notary/logs
! ATTENTION: This node is running in development mode!  This is not safe for production deployment.
Database connection url is              : jdbc:h2:tcp://localhost:10004/node
Advertised P2P messaging addresses      : localhost:10000
RPC connection address                  : localhost:10001
RPC admin connection address            : localhost:10002
Loaded 2 CorDapp(s)                     : Contract CorDapp: Corda Finance Demo version 1 by vendor R3 with licence Open Source (Apache 2), Workflow CorDapp: Corda Finance Demo version 1 by vendor R3 with licence Open Source (Apache 2)
Node for "Notary" started up and registered in 40.15 sec


Welcome to the Corda interactive shell.
Useful commands include 'help' to see what is available, and 'bye' to shut down the node.

Thu Dec 05 21:21:20 BRST 2019>>> 

```
