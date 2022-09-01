# IBM MQ
## Comandos
- `dspmq`: Exibe detalhes da Queue Manager que está rodando.
- `dspmqver`: Exibe detalhes da configuração;
- `runmqsc NOME_QUEUE_MANAGER`: Inicia conexão com o Queue Manager para executar comandos. Ex: `runmqsc QM1`
  - `DISPLAY CHANNEL(NOME_CANAL)`: Exibe informações do canal. Ex: `DISPLAY CHANNEL(DEV.APP.SVRCONN)`
  - `DISPLAY QUEUE('NOME_QUEUE')`: Exibe informações da fila. Ex: `DISPLAY QUEUE('purchase')`
