# Api usando Mongodb

### Ferramentas

* Ruby 3.0.1

* Rails 6.1.4

* MongoDB 2.4

Foi criado um projeto Ruby on Rails que exibe informações sobre alguns escritores e livros. 
Para cadastrar essas informações utilizaremos documentos em um  banco de dados MongoDB
Isso será feito com o auxílio de uma gem muito popular chamada Mongoid.

### Set up
Clone o repositorio em sua maquina, configure 

`git clone https://github.com/Jrolisilva/mongoApp.git`

`Bundle install `

Inicie o banco de dados e conecte o servidor

`sudo service mongod start`

`rails server`

### Exemplo do cadastro de autores.

![alt text](https://github.com/Jrolisilva/mongoApp/blob/master/img1.png)


### Cadastro de Livros vinculado com o autor

![alt text](https://github.com/Jrolisilva/mongoApp/blob/master/img2.png)

### Lista de Livros
![alt text](https://github.com/Jrolisilva/mongoApp/blob/master/img3.png)


