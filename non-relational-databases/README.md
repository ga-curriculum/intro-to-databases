# ![Non-Relational Databases - MongoDB](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to describe what a non-relational database is.

## Introduction to Non-Relational Databases

A non-relational database, often referred to as a NoSQL (Not Only SQL) database, is a type of database management system that does not follow the traditional relational database model. Unlike relational databases, which use a structured schema with tables, rows, and columns, non-relational databases use a variety of data models for storing and retrieving data.

## Document-Oriented Data Model

A document-oriented database is a type of NoSQL database management system that is designed to store, retrieve, and manage semi-structured or unstructured data in the form of documents.  The document-oriented data model that we will take a look at is MongoDB.  Specifically, we will look at how data is stored in documents and documents are stored in collections.

## Collections and Documents

In MongoDB, we save and retrieve documents to and from a collection.

Let's take a look at what a MongoDB _document_ might look like:

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

A _collection_ is a group of related documents within a MongoDB database. Collections serve as a container for organizing and storing documents. A document is a single record within a collection.