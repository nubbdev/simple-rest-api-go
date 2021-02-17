# Simple Rest Api with Golang and MySql
Simple Rest Api with Golang and MySql


Another dependencies included :
- github.com/gorilla/mux (protocol)
- github.com/go-sql-driver/mysql (database)
- github.com/joho/godotenv (environment)


Configuration :
1. git clone https://github.com/nubbdev/simple-rest-api-go.git
2. go get github.com/gorilla/mux
3. go get github.com/go-sql-driver/mysql
4. go get github.com/joho/godotenv
5. Create database and run query below
```
CREATE TABLE IF NOT EXISTS `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(50) NOT NULL DEFAULT '0',
  `last_name` varchar(50) NOT NULL DEFAULT '0',
  PRIMARY KEY (`id`)
)
```
6. Change your db on .env config files
7. Run command below (your position should in the clone directory)
```
go build
```
wait, then
```
. ./yourAppOnDirectory.exe
```
Happy coding