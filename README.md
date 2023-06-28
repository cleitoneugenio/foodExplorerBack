<img src="https://github.com/cleitoneugenio/foodExplorerBack/assets/122410611/c5605af2-c760-453e-a6f0-9a1f803115bb">

A aplicação desenvolvida é um cardápio digital para um restaurante fictício, conhecido como Food Explorer. Tecnologias usadas: HTML, CSS, JavaScript e React.js no [front-end](https://github.com/cleitoneugenio/foodExplorerFront) e NodeJs com Knex no back-end

## 🛠 Tecnologias

As seguintes tecnologias foram empregadas na no desenvolvimento do back-end:

- Node
- Bcryptjs
- Cors
- Dotenv
- Express
- Express-async-errors
- Jest
- Jsonwebtoken
- Knex
- Multer
- Nodemon
- pm2
- Sqlite
- Sqlite3

## 🧩 Funcionalidades

- [x] Um projeto estruturado, com uma boa organização das pastas, divisão de componentes no front-end, etc;
- [x] Os dados do admin, do restaurante e dos usuários serão armazenados em um banco de dados;
- [x] Os usuários deverão se autenticar para entrar na aplicação através da tela de login;
- [x] Dê nomes significativos para as suas funções e variáveis: trabalhe um pouco com os conceitos do Clean Code;
- [x] Possibilidade de fazer uma busca pelo nome do prato, pelos ingredientes ou por prato favorito;
- [x] O admin irá fazer upload de imagens para cadastrar e editar tanto os pratos quanto os ingredientes;
- [x] Interessante deixar a aplicação responsiva: utilize o conceito de Mobile First que foi aprendido em aula;
- [x] Deixe o código mais acessível e semântico usando as dicas que foram passadas em aula;
- [x] Fica a seu critério onde aplicar animações, transições e transformações;
- [x] É essencial que a sua interface consuma a sua API;
- [x] Para finalizar, faça o deploy da sua aplicação.

## 🎲 Como utilizar

```bash

# Clone o projeto para o local desejado em seu computador.
$ cd + sua pasta + git clone https://github.com/cleitoneugenio/foodExplorerBack.git

# Na raiz do projeto renomeie o arquivo .env.example para .env e insira uma porta para a aplicação rodar e um secret para utilizar o jwt no projeto 
PORT =
AUTH_SECRET =

# Instale as dependências com:
$ npm install

# Execute as migration e seed
$ npm migrate
$ npm seed

# Rode a aplicação em modo de desenvolvimento:
$ npm run dev

# O terminal irá exibir a frase 'Server is running on Port' e a porta onde a aplicação está sendo executada. 
# Server is running on Port {PORT definida no arquivo .env}
```

## 📌 Veja o resultado final

Você observará a união desse repositório com o [front-end](https://github.com/cleitoneugenio/foodExplorerFront)

⇨ [Resultado Final](https://foodexplorer-back-cleitoneugenio.netlify.app/)

### Quer ver como a aplicação funciona vista pelo administrador? Use a conta a seguir

`e-mail: admin@email.com` `senha: 112233`

O front-end desse projeto esta hospedado no [Netlify](https://www.netlify.com/) e o servidor está hospedado no [Render](https://render.com/) e por se tratar de serviços de hospedagem gratuito a velocidade não é seu forte então tenha um pouco de paciência 🤝🏾  

## 📝 License

This project is under the license [MIT](./LICENSE).
