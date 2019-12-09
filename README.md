# Todo app

## Backend
```
$ cd backend
```
### Mongo
install mongo

```
$ brew tap mongodb/brew
$ brew install mongodb-community@4.2
```
other options to install: https://docs.mongodb.com/manual/installation/

```
$ mongod
```

### Server Dev
```
npm run dev
```

### Server Production
To start production server with PM2
```
$ npm run production
```
#### To real time status PM2
```
$ pm2 monit
```

#### API EX
- `[GET] /api/todos`
- `[POST] /api/todos`
- `[DELETE] /api/todos/:id`
- `[PUT] /api/todos/:id`


## Frontend
Create new `packages.json`
```
npm init -y
```

### Install
```
$ cd ./frontend
$ npm i
````

### Start project
```
$ npm run dev
```
