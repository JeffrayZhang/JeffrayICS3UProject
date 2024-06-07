
# starter app

See it in production at https://jeff-app-frontend.vercel.app

![screenshot](https://github.com/davidmcnamee/jeff-app/assets/16356719/7087eace-80b5-4171-bede-98d94344db9c")


This is a starter web app that comes pre-configured with:
* a backend API written in typescript w/ express.js
* a prisma ORM configuration for postgres
* a react web app (using typescript)
* firebase authentication

## setup

1. clone the repo
   * `git clone https://github.com/davidmcnamee/jeff-app.git`
   * `cd jeff-app`
2. run `make setup`
4. run `createdb jeff-app` (this creates a postgres database on your local machine)
5. create a `.env` file based on `.env.example` (or ask David)
6. In one terminal, run `cd frontend && yarn start`
7. In another terminal, run `cd backend && yarn start`

