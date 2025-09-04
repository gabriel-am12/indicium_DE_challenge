# Data Enginner Challenge - **Indicium**

## Sobre

Implementação de uma **pipeline ETL**(Extração, Transformação, Carregamento) para o Banco Vitória(um banco fictício) utilizando Apache Airflow para orquestração de fluxos de trabalho e Docker para infraestrutura.

## Pré-requisitos e Execução

- [Python](https://www.python.org/downloads/)
- [Docker](https://www.docker.com/)
- [Docker Composer](https://docs.docker.com/compose/install/)
- [Git](https://git-scm.com/downloads)

---

1. ### Clonar o repositório

```bash
git clone git@github.com:gabriel-am12/indicium_DE_challenge.git
```

2. ### Subir os serviços

```bash
docker-compose up -d
```

3. ### Acessar o Airflow Webserver

```bash
http://localhost:8080
(usuário e senha = airflow)
```

4. ### Configure as Conexões do Airflow(Admin -> Connections)

```bash
Connection Id: banvic_source_db

Connection Type: Postgres

Host: db

Database: banvic

Login: data_engineer

Password: v3rysecur&pas5w0rd

Port: 5432
```
