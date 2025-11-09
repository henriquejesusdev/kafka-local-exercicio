# Ambiente Kafka Local com Docker Compose

## Serviços inclusos
- **ZooKeeper** (confluentinc/cp-zookeeper:7.6.0)
- **Kafka** (confluentinc/cp-kafka:7.6.0)
- **Kafka UI** (provectuslabs/kafka-ui:latest)

## Como executar

```bash
# 1. Clone ou copie os arquivos para uma pasta
# 2. Execute:
docker compose up -d --build

# 3. Aguarde alguns segundos até todos os containers ficarem saudáveis
docker compose ps

# 4. Acesse a interface web:
http://localhost:8080