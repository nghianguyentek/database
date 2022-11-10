# Database knowledge

A database is a collection of data containing information of an enterprise.

## DBMS

A database management system is databases and software to manipulate them in an efficient and convenient way.

## File-processing systems

Prior [DBMS](#dbms), data are stored in files in various formats and the way to manipulate them and they
are known as file-processing systems.

### Disadvantages of file-processing systems

- Data redundancy and inconsistency
- Data accessing difficulty.
- Data isolation.
- Integrity problems.
- Atomicity problems.
- Concurrent-access anomalies.
- Security problems.

## Data abstraction in DBMS

Users can manipulate data without knowing how data is stored or maintained.

### Data transaction levels

- Physical: the lower abstraction level describing the physical structures to store data.
- Logical: the middle abstraction level describing data logical structures and relationships between them.
- View: the highest abstraction level describing different portions of data.

## Database instances

A database instance is the database itself at a particular version based on using purpose, for example, multiple
environments such as development, testing, and production.

## Database schemas

A database schema is the design of a particular component of a database. These designs are categorised
according to the [data abstraction levels](#data-transaction-levels).

## Data models

A data model is how we identify information to a specific group, the semantics and constraints of each group, and the
relationship between these groups.

See [Data models](data-model/README.md).

## Database languages

Database language is a language used to interact with databases that often split
into [DDL](#ddl-data-definition-language) and [DML](#dml-data-manipulation-language) sub-languages.

### DDL (Data Definition Language)

DDL is used to work with [database schemas](#database-schemas) and constraints.

### DML (Data Manipulation Language)

DML is used to manipulate data including retrieving, insertion, updating, and deletion. There are two common types of
DML are [Procedural DML](#procedural-dml) and [Declarative DML](#declarative-dml).

#### Procedural DML

Procedural DML is a DML that requires to specify what data are needed and how to get them also.

#### Declarative DML

Declarative DML, also non-procedural DML, is a DML that requires to specify what data are needed without specifying how
to get them.