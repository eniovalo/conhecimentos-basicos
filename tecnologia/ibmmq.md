# IBM MQ
## Comandos
- `crtmqm NOME_QUEUE_MANAGER`: Cria um Queue Manager. Ex: `crtmqm QM1`
- `dspmq`: Exibe detalhes da Queue Manager que está rodando.
- `dspmqver`: Exibe detalhes da configuração;
- `endmqm NOME_QUEUE_MANAGER`: Para um Queue Manager. Ex: `endmqm QM1`
- `runmqsc NOME_QUEUE_MANAGER`: Inicia conexão com o Queue Manager para executar comandos. Ex: `runmqsc QM1`
  - `amqsget NOME_QUEUE NOME_QUEUE_MANAGER`: Obtém uma mensagem. Ex: `amqsget LQ1 QM1`
  - `amqsput NOME_QUEUE NOME_QUEUE_MANAGER`: Inicia a criação de uma mensagem. Depois digite a mensagem e tecle *ENTER*. Ex: `amqsput LQ1 QM1`
  - `DISPLAY CHANNEL(NOME_CANAL)`: Exibe informações do canal. Ex: `DISPLAY CHANNEL(DEV.APP.SVRCONN)`
  - `DISPLAY QUEUE('NOME_QUEUE')`: Exibe informações da fila. Ex: `DISPLAY QUEUE('purchase')`
  - `define qlocal(NOME_QUEUE)`: Cria uma fila. Ex: `define qlocal(LQ1)`
  - `end`: Sai do terminal de comandos.
- `strmqm NOME_QUEUE_MANAGER`: Inicia um Queue Manager. Ex: `strmqm QM1`
