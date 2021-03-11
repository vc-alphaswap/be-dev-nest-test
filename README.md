# be-dev-nest-test

You need to build a simple backend app with authentication and a private route using Nest.js and Typeorm. https://nestjs.com/
A user should signup/login with an email and a password. This data should be hashed and stored in the database with unique salt as well.

### What components should be there:
- [ ] Auth module (strategies)
- [ ] User module
- [ ] Database module
- [ ] Postgres database script in docker-compose.yml
- [ ] e2e tests that test the flow using the nest testing suite (signup, signin, protected route)
### What api endpoints should be there:
- [ ] /api/signup (should signup user and return jwt or throw error)
- [ ] /api/login (should login and return jwt or throw errors )
- [ ] /api/test (a protected route that should return the user object calling this endpoint)
### Bonus:
- [ ] use dtos, nestjs dto validation with class-validator, class-transformer
- [ ] you should not be able to inject variables that are not defined in the dto
- [ ] use enums
- [ ] user object returned from /api/test should not have sensitive fields (password, salt)

##### Good luck! 😊
