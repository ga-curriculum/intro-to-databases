# ![Non-Relational Databases - MongoDB](./assets/tktk-hero.png)

**Learning Objective:** By the end of this lesson, students will understand the concept of non-relational databases, specifically focusing on MongoDB as an example.

### What is a non-relational database?

Non-relational databases, commonly referred to as NoSQL databases, break away from the traditional relational database model. Instead of adhering to a fixed, table-based structure, non-relational databases are designed to handle a variety of data models. These models are more flexible and can manage semi-structured or unstructured data efficiently.

### Document-oriented databases: MongoDB

Among the types of NoSQL databases, document-oriented systems stand out for their versatility in managing data. [MongoDB](https://www.mongodb.com/), a leading document-oriented database, exemplifies this approach. It is engineered to store, manage, and retrieve data in the form of documents, which can be thought of as complex records with varying structures.

### Understanding collections and documents in MongoDB

tktk hunter - a super basic visual showing the document > collection hierarchy 

**Documents**: In MongoDB, data is stored as *documents*. These documents are similar to JSON objects and can contain a variety of key-value pairs. Documents are the basic unit of data in MongoDB, analogous to a row in a relational database. Instead of tables, documents are stored in what we call *collections*.

  Example of a MongoDB Document:

  ```javascript
  {
    _id: ObjectId("5099803df3f4948bd2f98391"),
    name: { first: "Alan", last: "Turing" },
    birth: ISODate("1912-06-23T00:00:00Z"),
    death: ISODate("1954-06-07T00:00:00Z"),
    contribs: [ "Turing machine", "Turing test", "Turingery" ],
    views: 1250000
  }
```
> A *collection* is a group of related documents within a MongoDB database. Collections serve as a container for organizing and storing documents. A document is a single record within a collection.
