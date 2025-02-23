# Ollama Docker Setup

Este repositório contém a configuração necessária para rodar o Ollama e o Open WebUI usando Docker.

## Pré-requisitos

- Docker instalado
- Docker Compose instalado

## Instruções

1. Clone este repositório:

    ```sh
    git clone <URL_DO_REPOSITORIO>
    cd <NOME_DO_REPOSITORIO>
    ```

2. Execute o Docker Compose:

    ```sh
    docker-compose up -d
    ```

    Isso irá iniciar os seguintes serviços:
    - `ollama`: Serviço principal do Ollama.
    - `ollama-model-loader`: Serviço para carregar os modelos no Ollama.
    - `open-webui`: Interface web para interagir com o Ollama.

3. Acesse a interface web:

    Abra o navegador e vá para `http://localhost:8080`.

## Parar os serviços

Para parar os serviços, execute:

```sh
docker-compose down
