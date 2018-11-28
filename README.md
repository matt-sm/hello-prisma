# hello-prisma
Prisma getting started

## Install
```
brew tap prisma/prisma
brew install prisma
npm install
```
## Deploy
```
docker-compose up -d
prisma deploy
prisma generate
```
## Run
```
node index.js
```
Then browse to http://localhost:4000
## Samples
```
mutation {
  createUser(name: "Bob") {
    id
  }
}
```