# Introduction

This workshop contains several hands-on labs that showcase some of the latest enhancements in the long term Oracle Database support release, 19c. Our mission is not just to manage your data but help you get value out of your data. For the world’s most demanding enterprise applications and workloads, Oracle Database 19c is a converged database that delivers a high performance, highly available, secure and scalable data management platform for cloud as well as on-premises environments.

## About Oracle Database 19c

The 19c generation of Oracle's converged database offers customers; best of breed support for all data types (e.g. relational, JSON, XML, spatial, graph, OLAP, etc.), and industry leading performance, scalability, availability and security for all their operational, analytical and other mixed workloads. Oracle database 19c is also the most advanced SQL engine in the world. It supports fully consistent data with ACID transaction guarantees along with consistent queries and it complies with the latest ISO SQL standard, making it not only the most comprehensive database but also the most open one. On top of the world class relational and transactional support, Oracle 19c supports a myriad of other workloads and data types like JSON in the database. JSON is supported natively with relational database features, including transactions, indexing, declarative querying, and views. This ability to support different workloads and data types goes back to the concept discussed earlier about the aspect of a converged database.

The converged database approach can be easily misunderstood as one large database where you store everything inside. Instead, the idea of this approach is that of the swiss army knife. You can use multiple different instance of the database that are each configured to the data model and workload type you require. With the converged database approach you don't have to deal with a variety of single purpose database architectures, different tooling, security models, patching schedules, upgrade paths, and integration issues. Every time you need a database of some sort(e.g. document, relational, spatial, graph, etc.) for some workload such as data warehousing, IoT, transactional, streaming, etc., you can use a configuration of the same converged database core engine tailored to that use case. You can also run different kinds of workloads on the same dataset if you desire. Along with this, Oracle database allows for each application module in a microservices architecture to be developed and deployed independently by providing a containerized data store in the form of pluggable databases inside the container database. This multitenant container architecture in the data tier provides consolidation, isolation, and agility for databases and it matches containerization in the app tier. For the scope of this lab we will be focusing on the top new features in Oracle 19c database.

19c is the latest long term release and delivers greatest technologies out to our customers. Users of 11g release 2 (11.2.0.4), 12c (12.1.0.2), 12c release 2(12.2.0.1), and 18c(12.2.0.2) can directly upgrade to Oracle Database 19c.

Watch this video below to learn more about Oracle database breakthrough innovations
[](youtube:recR8UR13o8)

## About the Oracle Database 19c New Features Workshop

This workshop lets you try out new features in Oracle Database 19c. All the labs are independent of each other, so you don't need to do them in any particular order. If needed, a lab starts with instructions on how to prepare your environment, and ends with instructions on how to restore your environment back to its original state.

### General Database 19c New Features Labs

The following labs are available:


**Application Development:**
- Case-Insensitive Database
- JSON in the Database
- Private Temporary Tables

**Availability:**
- Active Data Guard DML Redirection ** not on ADB
- Online Table Move

**Security:**
- Schema Only Accounts

**Analytics:**
- Approximate Count Distinct
- Approximate Query Processing
- Analytic Views
- Real-Time Materialized Views

**Database Overall:**
- Advanced Index Compression (TBD if adding to the list) 12.2 **its exa and exa/CC - does this mean ADB?
- Tracking Index Usage
- Easy Connect Plus
- Automatic Indexing
- Real-Time Statistics
- Blockchain Tables
- Immutable table

**Performance:**
- Database In-Memory Base Level **not ADB
- In-Memory External Tables **not ADB
- SQL Quarantine

**SQL Features:**
- Advanced
  - SQL macros scalar (on 21 but backported to 19c...)
  - SQL macros table(on 21 but backported to 19c...)
  - polymorphic table functions 18c+
- Partitioning
  - approx **!**
  - Table Creation for Partition Exchange 12.2+ **its exa and exa/CC - does this mean ADB?
  - Hybrid Partitioned Tables 19c+ **its exa and exa/CC - does this mean ADB?
- Improved existing features
  - DISTINCT Option for LISTAGG Aggregate 19c+ / Enhancing LISTAGG Functionality 12.2+
  - to_number (Expression Tracking) 12.2+ **its exa and exa/CC - does this mean ADB?
  - Enhancing CAST Function With Error Handling 12.2+
  - New SQL and PL/SQL Function VALIDATE_CONVERSION 12.2+


### Learn More

* [Oracle Database Blog](http://blogs.oracle.com/database)
* [Oracle Database Features and Licensing](https://apex.oracle.com/database-features/)
* [Introducing Oracle Database 19c](https://www.oracle.com/a/tech/docs/database19c-wp.pdf)

## Acknowledgements
* **Author** - Killian Lynch, Database Product Management
* **Contributors** - Thanks to the following for helping guide my ideas: Dominic Giles, Jenny Tsai-Smith, Kay Malcolm, Jody Glover, Matthew McDaniel
* **Last Updated By/Date** - Killian Lynch July 2022
