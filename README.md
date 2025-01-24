<h1 align="center" style="font-weight: bold;">GERENCIAMENTO DE ESTOQUE COM KAFKA</h1>

O Apache Kafka é uma plataforma de streamings de eventos distribuidos de e em tempo real. Assim pode atuar como um sistema de mensagens de alta performance confiável. Nesse projetos usamos ele para fazer a comunicação do serviço de estoque com o serviço de vendas.

<h3>Pré-requisitos:</h3>

- Kafka
- Offset Explorer (para podermos gerenciar os microserviços)
- Homebrew (para poder usar o kafka no macOS)

<h3>Inicializando: </h3>

```bash
   brew install kafka
   zookeeper-server-start /opt/homebrew/etc/kafka/zookeeper.properties
   kafka-server-start /opt/homebrew/etc/kafka/server.properties
```
<h3>Finalizando: </h3>

```bash
   brew services stop kafka
   brew services stop zookeeper
```
