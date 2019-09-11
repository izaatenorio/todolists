# Iniciar
$ npm i -g @adonisjs/cli
$ adonis serve --dev

# .env
HOST=127.0.0.1
PORT=3334
NODE_ENV=development
APP_URL=http://${HOST}:${PORT}
CACHE_VIEWS=false
APP_KEY=KyYp2tlOJ3Y7fbBKfPFAFRmPtbFBEPCx
DB_CONNECTION=pg
DB_HOST=127.0.0.1
DB_PORT=5432
DB_USER=postgres
DB_PASSWORD=rihanna
DB_DATABASE=todolist
SESSION_DRIVER=cookie
HASH_DRIVER=bcrypt



# Adonis fullstack application

This is the fullstack boilerplate for AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Session
3. Authentication
4. Web security middleware
5. CORS
6. Edge template engine
7. Lucid ORM
8. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
