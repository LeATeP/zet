# vaava server/efficiency of load, solutions

RAW

main topic is efficiency of solutions in realization of server/client/sql
game consist of containes, but containers have to communicate, save data, and be manageble

* solutins to container/network/data management


## 1. each client individually send data to process in sql server side

* each client have access to main server, and sql server
* the server only responsible for management and organization of each client, and assigning free units to them

pros
1. no need to think of hard logic of main server, that all client have to follow
1. direct access to database
1. each client have their own logic and mechanics, where server doesn't interfere

cons
1. no validation of transactions, no security 
1. constant management of database load, all computaion are in sql

## 2. the server responsible for all transaction with sql server

* each client only have main server access to transmite critical data
* the server will manage all variable and communicate with sql 

pros
1. no need to hard planning of scaling database servers, to meet damand of each client sending data
1. less workload on database, less database need of scaling
cons

## 3. main app solution

* no indivial division of workload on separate containers, only 1 main app
* by adding new threads, and concurency, new separate tasks can be add
* 

pros of this approach
1. no need to manage containers
1. client,server management
1. server/client/sql communication planning
cons






