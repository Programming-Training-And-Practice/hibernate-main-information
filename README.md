# Hibernate.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Pros.](#pros)
* [Cons.](#cons)
* [HQL Pros.](#hql-pros)
* [HQL Cons.](#hql-cons)
* [Help](#help)





## About.





## Documentation.





## Pros.
* Hibernate is an ORM tool
* Hibernate is an open source framework.
* Better than JBDC.
* Hibernate has an exception translator , which converts checked exceptions of JDBC in to unchecked exceptions of hibernate. 
  So all exceptions in hibernate are unchecked exceptions and because of this no need to handle exceptions explicitly.
* Hibernate supports inheritance and polymorphism.
* With hibernate we can manage the data stored across multiple tables, by applying relations(association)
* Hibernate has its own query language called Hibernate Query Language. With this HQL hibernate became database independent.
* Hibernate supports relationships like One-To-One, One-To-Many, Many-To-One ,Many-To-Many.
* Hibernate has Caching mechanism. using this number of database hits will be reduced. so performance of an application will be increases.
* Hibernate supports lot of databases.
* Hibernate supported databases List.
* Hibernate is a light weight framework because hibernate uses POJO classes for data transfer between application and database.
* Hibernate has versioning and time stamp feature with this we can know how many number of times data is modified.
* Hibernate also supports annotations along with XML.
* Hibernate supports Lazy loading.
* The architecture is layered to keep you isolated from having to know the underlying APIs.
* Hibernate maintains database connection pool.
* Hibernate  has Concurrency support.
* Using Hibernate its Easy to maintain and it will increases productivity.





## Cons.
* Lots of API to learn: A lot of effort is required to learn Hibernate. As many other tool, Hibernate also takes considerable 
  amount of time and effort to learn. I can’t say it is 100% disadvantage but yes it’s not so easy to learn. So because 
  of steep learning curve, we may consider it as disadvantage.
* Debugging: Sometimes debugging and performance tuning becomes difficult.
* Slower than JDBC: Hibernate is slower than pure JDBC as it is generating lots of SQL statements in runtime.
* Not suitable for Batch processing: It advisable to use pure JDBC for batch processing.
* Not suitable for Small projects : For small project having few tables it is useless to work with hibernate.
* Does not allow multiple inserts : Hibernate does not allow some type of queries which are supported by JDBC. 
  For example It does not allow to insert multiple objects (persistent data) to same table using single query. Developer
  has to write separate query to insert each object.
* Generates complex quires with many joins : For complex data, mapping from Object-to-tables and vise versa reduces 
  performance and increases time of conversion. (query conversion)
* Everything is returned as object : Yes that is true and even if you would like to get an id or name, you would write 
  the hql and get an object which has the complete data set. This is anyways not bad because while designing methods, 
  you will have coarse grained objects which well be returned. I would not prefer to return String or int from my methods.
* Learning curve:   





## HQL Pros.





## HQL Cons.
* HQL queries cannot perform DDL operations.
* HQL queries cannot insert single record into table.
* An HQL query gives negligible performance degradation because of conversions when compared to SQL.
* HQL queries cannot call PL/SQL program.






# Help.
