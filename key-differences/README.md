# ![[tktk Module Name] - tktk Microlesson Name](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to highlight key differences between relational and non-relational databases.

## Schema vs. Schema-less

Schema:

A schema is a blueprint or a formal definition that describes the organization of data in a database. It defines the tables, the fields (columns) within each table, the data types of the fields, and the relationships between tables.

Schema-less:

In a schema-less database, there is no predefined schema that dictates the structure of the data. Instead, the database allows for flexible and dynamic storage of data without requiring a fixed, rigid structure.


## Use Cases and When to Choose Each

Either a SQL database or MongoDB can be used for most applications.

However, in general:

- **Relational Databases** are preferred in financial applications such as banking, stock trading, etc., due to their strength in handling [**database transactions**](https://en.wikipedia.org/wiki/Database_transaction). However, they struggle with handling data that can’t be strictly organized into tables of structured columns because they have a strict **schema** (structure) they must adhere to.

- **Document-Based Databases like MongoDB** are preferred for storing vast amounts of unstructured data, such as social media applications. MongoDB is also a great choice when prototyping applications because it is **schema-less** and more adaptable to change.