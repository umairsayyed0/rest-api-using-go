# go-api-with-gorm
In this project, we have built a complete CRUD GO REST API with Gorilla Mux and GORM Library,and connected it with local mysql data base from work bench to perform CRUD operations
Here we have connected Local mysql data base from workbench in the programee(see [Line 20](https://github.com/sameerkhan97/go-api-with-gorm/blob/b790a9806bf2453da0d0b3efb8c468163477bef3/main.go#L20))
You can use any of the database like : 
* [postgresql](https://www.postgresql.org/)
* [sqlite](https://sqlite.org/index.html)


NOTE : you have to use the particular driver according to your db,as I have used mysql driver for this project

For more details : 
* [Gorilla Mux](https://github.com/gorilla/mux/)
* [ORM lib for Go](https://gorm.io/)

## Instructions to run code:
-  Clone the repo
     * git clone
 
- Before running the app
    * edit this [line](https://github.com/sameerkhan97/go-api-with-gorm/blob/b790a9806bf2453da0d0b3efb8c468163477bef3/main.go#L20) in the main file to connect with your mysql database

- Run the app using
     * in powershell use "go mod vendor" to synch the vendor directories 
     * now use specific file name to run the project
     * command go run main.go

 - Use POSTMAN for Testing
    * Test all routes,endpoints,operations(CRUD) using POSTMAN

