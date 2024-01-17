# ![Intro to Databases - Key Differences Between Relational and Non-Relational Databases](./assets/tktk-hero.png)

**Learning Objective:** This lesson will clarify the fundamental differences between relational and non-relational databases, helping students decide which to use based on specific application requirements.

## Exploring the differences and use cases

### Schema vs. schema-less databases

The core distinction between relational and non-relational databases lies in their data structure approach:

- **Schema in Relational Databases**:
  - A relational database uses a predefined schema to organize data into tables.
  - Each table consists of rows and columns, where columns define the data type and structure.
  - This rigid schema ensures consistent data entry and supports complex queries and relationships between different tables.
  
tktk Hunter - maybe reuse the table graphic from before, or something that represents schema

- **Schema-less in Non-Relational Databases**:
  - Non-relational databases, like MongoDB, do not require a predefined schema.
  - They allow dynamic storage of data, supporting various data formats without the need for a fixed structure.
  - This flexibility is ideal for handling unstructured or semi-structured data and can quickly adapt to changes in application requirements.
  
tktk Hunter - maybe reuse the document graphic from before, or something that represents no schema or looks like an object

### Selecting the right database for your application

The choice between a relational or non-relational database largely depends on an application's specific needs:

- **Relational Databases for Transaction-Heavy Applications**:
  - Ideal for financial applications (e.g., banking, stock trading) where handling [**database transactions**](https://en.wikipedia.org/wiki/Database_transaction) with accuracy and consistency is paramount.
  - Struggles with non-uniform data that cannot be neatly organized into structured tables.

- **Non-Relational Databases for Unstructured Data**:
  - Suited for applications dealing with large amounts of diverse data, like social media platforms.
  - MongoDB, a popular document-based non-relational database, offers high flexibility, making it a great choice for rapidly changing and evolving data models, as often seen in prototyping stages.

