## Home

Database Management System or DBMS refers to the technology of sorting, filtering and retrieving the data with utmost efficiency along with appropriate safety measures. 

### Why Learn DBMS

Traditionally data was organized in file formats. DBMS was a new concept then, and all the research was done to make it overcome the deficiencies of the traditional standard of data management. A modern DBMS has the following characteristics:
    ```
    1. Real World Entity - A modern DBMS is more realistic and uses real-world entities to design it's architecture. 
       It uses the behavior and attributes too. For example, a school database may use students as an entity and 
       their age as an attribute.
    
    2. Relation Based Tables - DBMS allows entities and relations among them to form tables. A user can understand 
       the architecture of a database just by looking at the table name and attributes.
    
    3. Isolation of data and application - A database system is entirely different than its data. A database is an 
       active entity, whereas data is said to be passive, on which the database works and organizes. DBMS also 
       stores metadata, which is data about data, to ease its own process.
    
    4. Less Redundancy - DBMS follows the rules of normalization, which splits a relation when any of its attributes
       is having redundancy in values. Normalization is a mathematically rich and scientific process that reduces 
       data redundancy.
    
    5. Consistency - Consistency is a state where every relation in a database remains consistent. There exist 
       methods and techniques, which can detect attempt of leaving database in inconsistent state. A DBMS can provide 
       greater consistency as compared to earlier forms of data storing applications like file-processing systems.
    
    6. Query Language - DBMS is equipped with query language, which makes it more efficient to retrieve and 
       manipulate data. A user can apply as many and as different filtering options as required to retrieve a set 
       of data. Traditionally it was not possible where file-processing system was used.
    ```

### Applications of DBMS

Database is a collection of related data and data is a collection of facts and figures that can be processed to produce information.

Mostly data represents recordable facts. Data aids in producing information, which is based on facts. For example, if we have data about marks obtained by all students, we can then conclude about toppers and average marks.

A database management system stores data in such a way that it becomes easier to retrieve, manipulate, and produce information. Following are the important characteristics and applications of DBMS.

    
    1. ACID Properties − DBMS follows the concepts of Atomicity, Consistency, Isolation, and Durability (normally 
       shortened as ACID). These concepts are applied on transactions, which manipulate data in a database. ACID 
       properties help the database stay healthy in multi-transactional environments and in case of failure.

    2. Multiuser and Concurrent Access − DBMS supports multi-user environment and allows them to access and 
       manipulate data in parallel. Though there are restrictions on transactions when users attempt to handle 
       the same data item, but users are always unaware of them.

    3. Multiple views − DBMS offers multiple views for different users. A user who is in the Sales department will
       have a different view of database than a person working in the Production department. This feature enables 
       the users to have a concentrate view of the database according to their requirements.

    4. Security − Features like multiple views offer security to some extent where users are unable to access data 
       of other users and departments. DBMS offers methods to impose constraints while entering data into the 
       database and retrieving the same at a later stage. DBMS offers many different levels of security features, 
       which enables multiple users to have different views with different features. For example, a user in the 
       Sales department cannot see the data that belongs to the Purchase department. Additionally, it can also be 
       managed how much data of the Sales department should be displayed to the user. Since a DBMS is not saved on 
       the disk as traditional file systems, it is very hard for miscreants to break the code.
    
## Overview

Database is a collection of related data and data is a collection of facts and figures that can be processed to produce information.

Mostly data represents recordable facts. Data aids in producing information, which is based on facts. For example, if we have data about marks obtained by all students, we can then conclude about toppers and average marks.

A database management system stores data in such a way that it becomes easier to retrieve, manipulate, and produce information.

### Characteristics

Traditionally, data was organized in file formats. DBMS was a new concept then, and all the research was done to make it overcome the deficiencies in traditional style of data management. A modern DBMS has the following characteristics.

    1. Real World Entity - A modern DBMS is more realistic and uses real-world entities to design it's architecture. 
       It uses the behavior and attributes too. For example, a school database may use students as an entity and 
       their age as an attribute.
    
    2. Relation Based Tables - DBMS allows entities and relations among them to form tables. A user can understand 
       the architecture of a database just by looking at the table name and attributes.
    
    3. Isolation of data and application - A database system is entirely different than its data. A database is an 
       active entity, whereas data is said to be passive, on which the database works and organizes. DBMS also 
       stores metadata, which is data about data, to ease its own process.
    
    4. Less Redundancy - DBMS follows the rules of normalization, which splits a relation when any of its attributes
       is having redundancy in values. Normalization is a mathematically rich and scientific process that reduces 
       data redundancy.
    
    5. Consistency - Consistency is a state where every relation in a database remains consistent. There exist 
       methods and techniques, which can detect attempt of leaving database in inconsistent state. A DBMS can provide 
       greater consistency as compared to earlier forms of data storing applications like file-processing systems.
    
    6. Query Language - DBMS is equipped with query language, which makes it more efficient to retrieve and 
       manipulate data. A user can apply as many and as different filtering options as required to retrieve a set 
       of data. Traditionally it was not possible where file-processing system was used.

    7. ACID Properties − DBMS follows the concepts of Atomicity, Consistency, Isolation, and Durability (normally 
       shortened as ACID). These concepts are applied on transactions, which manipulate data in a database. ACID 
       properties help the database stay healthy in multi-transactional environments and in case of failure.

    8. Multiuser and Concurrent Access − DBMS supports multi-user environment and allows them to access and 
       manipulate data in parallel. Though there are restrictions on transactions when users attempt to handle 
       the same data item, but users are always unaware of them.

    9. Multiple views − DBMS offers multiple views for different users. A user who is in the Sales department will
       have a different view of database than a person working in the Production department. This feature enables 
       the users to have a concentrate view of the database according to their requirements.

    10. Security − Features like multiple views offer security to some extent where users are unable to access data 
       of other users and departments. DBMS offers methods to impose constraints while entering data into the 
       database and retrieving the same at a later stage. DBMS offers many different levels of security features, 
       which enables multiple users to have different views with different features. For example, a user in the 
       Sales department cannot see the data that belongs to the Purchase department. Additionally, it can also be 
       managed how much data of the Sales department should be displayed to the user. Since a DBMS is not saved on 
       the disk as traditional file systems, it is very hard for miscreants to break the code.

### Users

A regular DBMS has users with varying rights and permissions for different purposes. Some users retrieve data, while others perform data backups. The users of a DBMS can generally be classified as follows:
   ```
   1. Administrators - Administrators maintain the DBMS and have the responsibility of managing the database. They 
      oversee its usage and determine who can access it. They create user profiles and enforce restrictions to ensure 
      security and isolation. Administrators also handle DBMS resources like system licenses, necessary tools, and 
      maintenance of software and hardware.

   2. Designers are the individuals who focus on the design aspects of the database. They carefully consider what 
      data needs to be stored and in what format. They identify and design the complete set of entities, relationships, 
      constraints, and views.

   3. End users are the ones who directly benefit from having a DBMS. They can range from casual observers who review 
      logs or market rates to sophisticated users like business analysts.
   ```

## Architecture

The way a DBMS is designed depends on its architecture. It can be centralized, decentralized, or hierarchical. The architecture of a DBMS can be classified as either single-tier or multi-tier. In a multi-tier architecture, the entire system is divided into n modules that are related but independent. These modules can be modified, altered, changed, or replaced independently.

### 1-tier architecture
In 1-Tier Architecture the database is directly available to the user, the user can directly sit on the DBMS and use it that is, the client, server, and Database are all present on the same machine. For Example: to learn SQL we set up an SQL server and the database on the local system. This enables us to directly interact with the relational database and execute operations. The industry won’t use this architecture they logically go for 2-Tier and 3-Tier Architecture.

#### Advantages of 1-tier architecture
- Simple Architecture: 1-Tier Architecture is the most simple architecture to set up, as only a single machine is required to maintain it.
- Cost-Effective: No additional hardware is required for implementing 1-Tier Architecture, which makes it cost-effective.
- Easy to Implement: 1-Tier Architecture can be easily deployed, and hence it is mostly used in small projects. 

![1-tier architecture](./img/DBMS-1-Tier-Architecture.webp)

### 2-tier architecture
The 2-tier architecture is similar to a basic client-server model. The application at the client end directly communicates with the database on the server side. APIs like ODBC and JDBC are used for this interaction. The server side is responsible for providing query processing and transaction management functionalities. On the client side, the user interfaces and application programs are run. The application on the client side establishes a connection with the server side in order to communicate with the DBMS. 
An advantage of this type is that maintenance and understanding are easier, and compatible with existing systems. However, this model gives poor performance when there are a large number of users. 

#### Advantages of 2-tier architecture
- Easy to Access: 2-Tier Architecture makes easy access to the database, which makes fast retrieval.
- Scalable: We can scale the database easily, by adding clients or by upgrading hardware.
- Low Cost: 2-Tier Architecture is cheaper than 3-Tier Architecture and Multi-Tier Architecture.
- Easy Deployment: 2-Tier Architecture is easy to deploy than 3-Tier Architecture.
- Simple: 2-Tier Architecture is easily understandable as well as simple because of only two components.

![2-tier-architecture](./img/DBMS%202-Tier%20Architecture.png)

### 3-tier architecture
In 3-Tier Architecture, there is another layer between the client and the server. The client does not directly communicate with the server. Instead, it interacts with an application server which further communicates with the database system and then the query processing and transaction management takes place. This intermediate layer acts as a medium for the exchange of partially processed data between the server and the client. This type of architecture is used in the case of large web applications. 

#### Advantages of 3-tier architecture
- Enhanced scalability: Scalability is enhanced due to distributed deployment of application servers. Now, individual connections need not be made between the client and server.
- Data Integrity: 3-Tier Architecture maintains Data Integrity. Since there is a middle layer between the client and the server, data corruption can be avoided/removed.
- Security: 3-Tier Architecture Improves Security. This type of model prevents direct interaction of the client with the server thereby reducing access to unauthorized data.

#### Disadvantages of 3-tier Architecture

- More Complex: 3-Tier Architecture is more complex in comparison to 2-Tier Architecture. Communication Points are also doubled in 3-Tier Architecture.
- Difficult to Interact: It becomes difficult for this sort of interaction to take place due to the presence of middle layers.

![3-tier architecture](./img/DBMS%203-Tier%20Architecture.png)

###