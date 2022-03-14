# NestJs REST API by GilbertHuarcaya

### Run the API in development mode
```javascript
yarn // install
yarn db:dev:restart // start postgres in docker and push migrations
yarn start:dev // start api in dev mode
```

## Used PRISMA ORM
### Run
```javascript
npx prisma studio // to see prisma studio with your postgres tables
```

### Run tests
```javascript
yarn test:e2e // to create a testdb and run all tests
```
