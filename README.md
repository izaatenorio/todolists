# Iniciar
$ npm i -g @adonisjs/cli <br>
$ adonis serve --dev

# .env
HOST=127.0.0.1 <br>
PORT=3334 <br>
NODE_ENV=development <br>
APP_URL=http://${HOST}:${PORT} <br>
CACHE_VIEWS=false <br>
APP_KEY=KyYp2tlOJ3Y7fbBKfPFAFRmPtbFBEPCx <br>
DB_CONNECTION=pg <br>
DB_HOST=127.0.0.1 <br>
DB_PORT=5432 <br>
DB_USER=postgres <br>
DB_PASSWORD=rihanna <br>
DB_DATABASE=todolist <br>
SESSION_DRIVER=cookie <br>
HASH_DRIVER=bcrypt <br>



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
