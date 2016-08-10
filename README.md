# foodmanagement
###Gerenciador de pedidos, em ramo alimentício.

##Download
Dentro de seu workspace crie a pasta:
```bash
    mkdir foodmanagement
    cd foodmanagement
```
Inicie o git, e clone o repositório.
```bash
    git init
    git clone https://github.com/marco-oliveira/foodmanagement.git
```

##Configuração
Aconselhavel utilizar a IDE baseada em Eclipse Spring Tools Suite. Encontrada
    (https://spring.io/tools/sts).
    
Para funcionar, o projeto deve ser importado como Maven Project,
criar um banco de dados em mysql, com o nome: "foodmanagement"(sem aspas),
esta configurado como padrão o usuario: "root" e senha: "root",
para utilizar de acordo com seu banco, altere o arquivo ```application.properties```
mudando o usuario e senha:
```html
spring.datasource.username="usuario_aqui"
spring.datasource.password="senha_aqui"
```
(sem aspas)

Execute a classe ```Foodmanagement.java``` como "Spring Boot App"
e acesse [localhost](http://localhost:8080/)
