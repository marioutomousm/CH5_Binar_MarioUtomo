# Binar: Express.js

Repository ini ditujukan sebagai boilerplate dalam membuat sebuah HTTP Server menggunakan Express.js
Repository ini menggunakan Service Repository Pattern, yang artinya di dalam repository ini terdapat modul model, controller, service, dan repository.

## Getting Started

Perintah untuk menginstall 

```sh
npm i 
```
## Database Management

Perintah untuk membuat database

```sh
npm sequelize db:create
```

Perintah untuk melakukan migrate yang berfungsi untuk membuat atau perubahan pada tabel-tabel di database

```sh
npm sequelize db:migrate
```

Perintah untuk melakukan penambahan data super admin

```sh
npm sequelize db:seed:all
```

Perintah untuk menjalankan development server dengan salah satu script di package.json, yang namanya `develop`.

```sh
npm run develop
```

## API Documentation

| Documentation type | Link | Details |
|--|--|--|
| OpenAPI Swagger UI | http://localhost:8000 <br> http://localhost:8000/api-docs |





Data super admin untuk login

```json
"email": "superadmin@gmail.com",
"password": "adminsuper"
```


API Document

```js
http://localhost:8081/api-docs
```