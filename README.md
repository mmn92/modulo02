## Backend example application

This application was made as an example to practice backend skills and tools.

### Tools used:

- Node.js
- Express
- Sucrase
- Nodemon
- ESLint
- Prettier
- Sequelize
- Postgres
- JWT
- Yup

## Routes

- `POST` `/users` : Creates a new user with the `name` and `email` sent in request body

- `POST` `/sessions` : Creates a new session after authenticating the user via jwt

- `PUT` `/users` : Updates the name, email or password of the user authenticated with `name`, `email` or `password` in request body

This application will be part of a larger project in the future
