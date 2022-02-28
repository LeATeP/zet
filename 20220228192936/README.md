# vaava server/efficiency of load, solutions

RAW

main topic is efficiency of solutions in realization of server/client/sql
game consist of containes, but containers have to communicate, save data, and be manageble

* solutins to container/network/data management


## 1. each client individually send data to process in sql server side

* each client have access to main server, and sql server
* the server only responsible for management and organization of each client, and assigning free units to them

pros
cons

## 2. the server responsible for all transaction with sql server

* each client only have main server access to transmite critical data
* the server will manage all variable and communicate with sql 

pros
1. no need to hard planning of scaling database servers, to meet damand of each client sending data


## 3. main app solution

* no indivial division of workload on separate containers, only 1 main app
* by adding new threads, and concurency, new separate tasks can be add
* 

pros of this approach
1. no need to manage containers
1. client,server management
1. server/client/sql communication planning







