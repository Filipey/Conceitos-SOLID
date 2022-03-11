## API Refactor utilizando os conceitos SOLID e documentando com Swagger

---

## Rotas

```
[POST] /users
[PATCH] /users/:user_id/admin
[GET] /users/:user_id
[GET] /users
```

### Testes

---

## Models

- [x] Should be able to create an user with all props

---

## Repositories

- [x]  Should be able to create new users
- [x]  Should be able to list all users
- [x] Should be able to find user by ID
- [x] Should be able to find user by e-mail address
- [x] Should be able to turn an user as admin

---

## useCases

- [x] Should be able to create new users
- [x] Should not be able to create new users when email is already taken
- [x] Should be able to turn an user as admin
- [x] Should not be able to turn a non existing user as admin
- [x] Should be able to get user profile by ID
- [x] Should not be able to show profile of a non existing user
- [x] Should be able to list all users
- [x] Should not be able to a non admin user get list of all users
- [x] Should not be able to a non existing user get list of all users