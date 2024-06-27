# MongoSH Commands Guide

## Table of Contents

- [Introduction](#introduction)
- [Connecting to MongoDB](#connecting-to-mongodb)
- [Database Commands](#database-commands)
- [Collection Commands](#collection-commands)
- [Document Commands](#document-commands)
- [Indexes](#indexes)
- [Aggregation](#aggregation)
- [Utilities](#utilities)

## Introduction

`mongosh` is the MongoDB Shell, a command-line interface for interacting with your MongoDB instances. It allows you to perform database operations, queries, and administrative tasks.

## Connecting to MongoDB

To connect to a MongoDB instance, use the following command:

```shell
mongosh "mongodb://<username>:<password>@<host>:<port>/<database>"
mongosh "mongodb://admin:password@localhost:27017/mydatabase"
