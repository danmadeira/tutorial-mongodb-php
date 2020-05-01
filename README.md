## Tutorial do MongoDB com PHP da ZetCode

Códigos de exemplo do tutorial da ZetCode sobre como trabalhar com MongoDB no PHP.

### Como começar:

Pelo MongoDB shell, o tutorial instrui a criar a base e inserir os dados.
```
$ mongo testdb
MongoDB shell version: 2.4.9
connecting to: testdb
> db
testdb
> db.cars.insert({name: "Audi", price: 52642})
> db.cars.insert({name: "Mercedes", price: 57127})
> db.cars.insert({name: "Skoda", price: 9000})
> db.cars.insert({name: "Volvo", price: 29000})
> db.cars.insert({name: "Bentley", price: 350000})
> db.cars.insert({name: "Citroen", price: 21000})
> db.cars.insert({name: "Hummer", price: 41400})
> db.cars.insert({name: "Volkswagen", price: 21600})
```

### Referência:

- ZetCode MongoDB PHP tutorial. Disponível em: <http://zetcode.com/db/mongodbphp/>
