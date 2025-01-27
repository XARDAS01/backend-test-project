# Wallet Service

## Popis projektu

Wallet Service je aplikace pro testovací úkol na správu peněženek.

## Požadavky

- Docker 20.10 nebo novější
- Docker Compose 1.29 nebo novější

## Instalace a spuštění pomocí Dockeru

### 1. Klonování repozitáře

Klonujte repozitář do vašeho lokálního počítače:

```properties
git clone git@github.com:XARDAS01/backend-test-project.git
cd wallet
cd wallet-devops
cd docker
```

### 2. Sestavení a spuštění projektu

```properties
docker-compose up --build -d
```

### 3. Logy

```properties
docker logs -f <containerId>
```

### 4. Zastavení aplikace

```properties
docker-compose down
```

## Swagger API

### Swagger je k dispozici na odkazu
```properties
http://localhost:8081/swagger-ui/index.html#/
```