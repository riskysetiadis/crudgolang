# crudgolang
this golang crud using my sql database and html as front end

1. first you need install xampp.
2. run xampp.
3. start apache and my sql.
4. create database experiment.
5. create table employe as this follow.
   
   CREATE TABLE `employee` (
  `id` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(30) NOT NULL,
  `city` varchar(30) NOT NULL,
  PRIMARY KEY (`id`)
  ) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
   
7. if you don't have golang you must to install (https://go.dev/doc/install).
8. then install this lib to your golang: go get -u github.com/go-sql-driver/mysql
9. git clone this repo
10. run it with : go run main.go
