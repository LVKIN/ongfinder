
# 🔎 ONG Finder

O ONG Finder tem o objetivo de facilitar a localização de ONG's próximas de sua geolicalização.

## 🔗 URL's


## 🛠 Stack


## ⚠️ Requerimentos

- Node v16+
- NPM

## 🗃 Variaveis de ambiênte

Caso queira trocar a porta padrão utilizada pela aplicação.

| Variable | Description |
| --- | --- |
| `PORT` | Define a porta utilizada pelo serviço Sample: PORT=3333 |

## 🎬 Instalação

- Primeiro clonar o projeto `git clone https://github.com/gallodev/ongfinder/api` 

- Entrar no diretório `api` e executar o comando `docker-compose up -d` ou `npm run docker-compose` para subir os serviços de banco de dados

- Após concluir executar o comando `docker run -p 3333:3333 -d gallodev/ongfinder` ou `npm run docker-up`

- Depois em seu navegador acesse [http://localhost:3333](http://localhost:3333) ou a porta personalizada de acordo com o seu env.

- 📁 repositório: [https://github.com/gallodev/ongfinder/api](https://github.com/gallodev/ongfinder/api)

## 🗂 Folder structure

```bash
📦 src
 ├── 📂 controllers
 ├── 📂 libs
 ├── 📂 services
 ├── 📜 app.ts
 ├── 📜 router.ts
 └── 📜 server.ts
```