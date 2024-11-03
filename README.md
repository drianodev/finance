# Finance Project

Este repositório centraliza todos os submódulos relacionados ao projeto Finance. O objetivo deste projeto é facilitar o gerenciamento financeiro.

## Submódulos

Este repositório utiliza submódulos para gerenciar diferentes partes do projeto. Para clonar o repositório com todos os submódulos, use o seguinte comando:

```bash
git clone --recurse-submodules git@github.com:drianodev/finance.git
```

Se você já clonou o repositório e deseja atualizar os submódulos, execute:

```bash
git submodule update --init --recursive
```

## Configuração

### Pré-requisitos

Antes de começar, verifique se você possui as seguintes ferramentas instaladas:

- [Git](https://git-scm.com/)
- [Java JDK 21](https://jdk.java.net/21/)
- [Maven](https://maven.apache.org/)
- [Node.js 20.12.2](https://nodejs.org/)

### Configuração da API

1. Navegue até o diretório da API:

    ```bash
    cd finance-api
    ```

2. Instale as dependências e inicie a aplicação:

    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

### Configuração do Frontend

1. Navegue até o diretório do frontend:

    ```bash
    cd finance-ap
    ```

2. Instale as dependências e inicie a aplicação:

    ```bash
    npm install
    npm run dev
    ```
