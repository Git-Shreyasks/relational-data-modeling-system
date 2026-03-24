# Data Modeling and Database Design System

A structured data modeling project that designs and implements a relational database system using entity-relationship modeling, normalization, and SQL-based querying.

---

##  Overview

This project focuses on designing a robust database system by identifying entities, defining relationships, and implementing an efficient relational schema.

The goal is to ensure:

* Data integrity
* Efficient querying
* Scalable database design

---

##  Key Concepts

* Entity-Relationship (ER) Modeling
* Relational Schema Design
* Normalization (1NF, 2NF, 3NF)
* SQL Query Design
* Data Integrity Constraints

---

##  System Design

The system models real-world entities and their relationships, converting them into a normalized relational schema.

---

##  ER Diagram

![ER Diagram](schema/er_diagram.png)

---

## ⚙️ Implementation

* Designed relational schema using normalized tables
* Implemented SQL queries for data retrieval
* Ensured integrity using constraints and relationships

---

##  Example Queries

```sql
SELECT * FROM Airport;
SELECT name, location FROM Flights WHERE status = 'Active';
```

---

##  How to Run

1. Import schema:

```bash
source schema/relational_schema.sql
```

2. Load data:

```bash
LOAD DATA INFILE 'data/sample_data.csv';
```

3. Run queries:

```bash
source queries/queries.sql
```

---

##  Tech Stack

* SQL
* Relational Databases
* CSV Data

---

##  Design Trade-offs

* Normalization improves integrity but may increase query complexity
* Denormalization can improve performance but risks redundancy

---

##  Applications

* Airline systems
* Inventory management
* Enterprise data systems
* Analytics pipelines

---

##  Contributors

* Shreyas K S
