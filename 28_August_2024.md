### MongoDB
MongoDB is a popular open-source NoSQL database. Unlike traditional relational databases that use tables and rows, MongoDB stores data in flexible, JSON-like documents (BSON - Binary JSON). This document-oriented approach allows for more complex and hierarchical data structures, making it easier to handle unstructured or semi-structured data.

No Sql: Document form mein key-pairs pairs <br>

BSON: Much faster than JSON <br>

Options for MongoDB: <br>
1. Atlas (cloud based momgo db server) <br>
2. Compass (local server) <br>

What we will do: <br>
1. CLI <br>
2. GUI <br>
3. ExpressJS with MongoDB <br>

Mongosh: shell to connect CLI version <br>

step1: create a server of mongodb <br>

D1 Database od chitkara has multiple collections: users, faca, students <br>

collections are in documents [key value pairs] <br>

## Commands:
1. mongosh:for checking version and installation. <br>
2. show dbs:for check databases <br>
3. use database_name:for creating database <br>
4. db.createCollection("Collection_name"):for craeting collections. <br>
5. db.collection.insertOne():for inserting single document inside collection. <br>
