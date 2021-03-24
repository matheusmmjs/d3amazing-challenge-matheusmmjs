<h1 align="center">Ultimate Bot - Backend</h1>
<p align="center">🚀 API onde será possível fazer as regras de negócio.</p>

### 🔍 Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Docker](https://www.docker.com/products/docker-desktop), [Docker Compose](https://docs.docker.com/compose/install/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Golang](https://golang.org/)
- [Nginx](https://www.nginx.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)

### ⚙️ Como executar o projeto localmente

1 - Para iniciar o desenvolvimento, é necessário clonar o projeto do GitHub num diretório de sua preferência:

```bash
cd "diretório de sua preferencia"
git clone https://github.com/d3estudio/d3amazing-challenge-matheusmmjs.git
```

2 - Acesse a pasta do projeto no terminal/cmd:

```bash
$ cd "diretório onde o projeto foi clonado"
```

3 - Execute o docker-compose up --build:

4 - Ao executar o docker-compose up --build será baixado automaticamente ferramentas necessárias para o projeto. Quando a instalações automáticas finalizarem o projeto pode ser acessado pelo navegador em [http://localhost/api](http://localhost/api).

### 🚧 Endpoints

- [GET] Hello:

```ruby
Envio:
localhost/api

Retorno:
"Hello, i'm a golang microservice"
```

### ✨ Informações adicionais

./db inclui os arquivos relativos ao container de base de dados inclusive versionamento.

./nginx configuracoes para proxy que cuida da renovacao de certificados.

./app aplicação em golang, onde é feito as regras de negócio.
