# Docker + Postgres

1. Docker 
- Docker là gì?
    - Local experiments
    - Integration test (CI/CD)
    - Reproducibility
    - Running pipelines on the cloud (AWS Batch, Kubernetes jobs)
    - Spark -- define data pipeline
    - Serverless (AWS Lambda, Google functions) -- processing data  1 record at time

- Run Postgres locally with docker

    > **Postgres** : là 1 database
    >
    >**pgAdmin** :  lầ công cụ thông dụng nhất để quản lý và thao tác với PostgreSQ



- Put data to local Postgres for testingg (Python)

- Packaging script to docker

- Run Postgres and scripts in a network

- Docker compose and running pgadmin and Postgres together

**Note**: run <code>docker inspect [name]</code> and find the **Gateway** of **pg-network**