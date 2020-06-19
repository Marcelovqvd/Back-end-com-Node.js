<p align="center">
  <img  src="./assets/Node.js_logo.svg">
</p>

# Back-end com Node.JS

  Projeto para fins de estudo dentro da Rocketseat - Bootcamp GoStack 2020

## :rocket: Início

        yarn init -y

        app.use(express.json()); Para que a API possa ler JSON

## Libs instaladas

#### Nodemon

        yarn add nodemon -D

Para criar scripts para nodemon

#### uuidv4

        yarn add uuidv4 - Gerar id automaticamente

### Rotas da aplicação

- **`POST /projects`**: A rota deve receber `title`, `owner` e `techs` dentro do corpo da requisição.

- **`GET /projects`**: Rota que lista todos os repositórios com filtro em Query Params.

- **`PUT /projects/:id`**: A rota deve alterar apenas o `title` e o `owner` que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /projects/:id`**: A rota deve deletar o repositório com o `id` presente nos parâmetros da rota;

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Finalizado