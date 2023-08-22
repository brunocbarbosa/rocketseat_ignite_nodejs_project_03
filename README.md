# App

GymPass style app

## Functional Requiriments

- [x] Should be posssible to register yourself;
- [x] Should be posssible to autenticate yourself;
- [x] Should be posssible get a logged user profile;
- [x] Should be posssible get the check-ins number number realized by logged user;
- [x] Should be posssible user get your chek-ins history;
- [x] Should be posssible user get near academies;
- [x] Should be posssible user search gym by name;
- [x] Should be posssible user realize check-in in one gym;
- [x] Should be posssible validate a user check-in;
- [x] Should be posssible to register a gym 

## Business Rules

- [x] The user should not register with duplicate email;
- [x] The user should not do 2 check-ins twice in the same day;
- [x] The user should not do check-in if isn't near (100m) of the gym;
- [x] The check-in only can be validated up to 20 minutes after created;
- [x] The check-in only can be validated by administrators;
- [x] The gym only can be registered by administrators;
  
## Not Functional Resources

- [x] User password have to be encrypted;
- [x] Aplication data have to stored in a PosgreSQL database;
- [x] All data list have to be paged with 20 items per page;
- [x] User have to be identified by a JWT;