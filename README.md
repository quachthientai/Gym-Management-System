# Gym Management System [![Java CI with Maven](https://github.com/quachthientai/Gym-Management-System/actions/workflows/maven.yml/badge.svg)](https://github.com/quachthientai/Gym-Management-System/actions/workflows/maven.yml) [![BUILT WITH](https://img.shields.io/badge/BUILT%20WITH-Netbeans-blue)](https://netbeans.apache.org/) [![CodeFactor](https://www.codefactor.io/repository/github/quachthientai/gym-management-system/badge)](https://www.codefactor.io/repository/github/quachthientai/gym-management-system)
The GMS (Gym Management System) project is the software program that tracks, maintains, and manages all the member and staff data, entirely constructed at the administrative level, only the administration has access, it was developed in Java Programming using NetBeansIDE, JFrame, and MySQL Database. That project will assist gym managers to manage their customers, and staffs. 
- Front-end: Friendly user-interface with Java Swing  
- Back-end: Handled by the SQL database via JDBC API to communicate with MySQL.
- Administrative level: provided username and password {admin,admin}
- Record of Member, Payment, and Trainer
## System Requirements
To execute the below project, you will need the following requirements:
- [MySQL Community Server](https://www.edureka.co/blog/install-mysql/)
- MySQL JDBC Connector
- [Java](https://www.oracle.com/java/technologies/downloads/)
- [NetBeans IDE](https://netbeans.apache.org/)
## Screenshots
### Log In 
- The user will be an admin by default, and the username and password will be {admin, admin}

![Login Page](https://github.com/quachthientai/Gym-Management-System/blob/master/screenshots/login.png)

### Homepage
- The admin menu as below, consists of Add Member, Manage Member, Trainers, Members List, Payments, and Log out

![Home Page](https://github.com/quachthientai/Gym-Management-System/blob/master/screenshots/homepage.png)

### Add Member page
- To add member, click on the option "Add Members" from admin menu

![Add Member page](https://github.com/quachthientai/Gym-Management-System/blob/master/screenshots/addmemberpage.png)

### Manage Member page
- To manage member, click on the option "Manage Members" from admin menu

![Manage Member page](https://github.com/quachthientai/Gym-Management-System/blob/master/screenshots/managememberpage.png)

### Trainers page
- To add/manage trainer, click on the option "Trainers" from admin menu

![Trainers page](https://github.com/quachthientai/Gym-Management-System/blob/master/screenshots/trainerpage.png)

### Members List page
- To view the members, click on the option "Members List" from admin menu

![Members List page](https://github.com/quachthientai/Gym-Management-System/blob/master/screenshots/memberlist.png)

### Payments page
- To manage payments, click on the option "Payments" from admin menu

![Payments page](https://github.com/quachthientai/Gym-Management-System/blob/master/screenshots/paymentpage.png)

## Getting started 
- To get the database first create a database in MySQL and then put the gmsdb_dump.sql dump file in your MySQL Server 8.0\bin directory. Now in command prompt enter:

  - cd Program Files/MySQL/MySQL Server8.0/bin “press enter"
  - mysql –u root –p database_name < database_name.sql “press enter”
  
  This will complete the database transfer to your computer.
## Contributor
- Tai Quach <quachthientai@gmail.com>
## License & copyright
Licensed under the [![Apche License](https://img.shields.io/github/license/quachthientai/gym-management-system?style=plastic)](LICENSE)
