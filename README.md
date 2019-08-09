


nestjs typeORM mysql CRUD

ref:  
https://www.techiediaries.com/nestjs-tutorial-rest-api-crud/


Notice: service should be follow the command.  
```
nest generate service contacts
```

```
yarn 
yarn start:dev
```

crud url:

http://localhost:3000/contacts/create

http://localhost:3000/contacts

http://localhost:3000/contacts/1/update

http://localhost:3000/contacts/1/delete

body:
```
{
	"firstName":"Zevi",
	"lastName":"Liao",
	"email":"jointjm@gmail.com",
	"phone":"09xx123123",
	"city":"paris",
	"country":"france"
}
```