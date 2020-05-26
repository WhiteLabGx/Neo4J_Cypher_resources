![](/home/Logo_horizontal.png)

****

# All you need to get started with Neo4J & Cypher

1. O'Reilly books
2. links to tutorials & repositories
3. installation instructions

* TOC {:toc}

#==> corrections needed for automatic table of content generation.


## O'Reilly books : 
- [Graph Databases](/Neo4J_Cypher_resources/OreillyGraphDatabases)
- [Graph Algorithms](/Neo4J_Cypher_resources/Neo4j_Graph_Algorithms.pdf)

## links to tutorials & repositories
tdb.

## installation instructions

1. Get neo4J Desktop  [installation guide here](https://neo4j.com/download-thanks-desktop/?edition=desktop&flavour=unix&release=1.2.8&offline=true)

## notes on Neo4J :

### Introduction : 

- graphs are everywhere, graph theory is at least 300 years old. 

- relationnal vs graph :

Main problem is managing not just a lot of individual, isolated, and discrete data items, but also the connections between them. And while the the discrete data can  be easily fit in relational tables, the connected data is more challenging to store and tremendously slow to query.

examples of graph databases :

    -- facebook => social graph
    -- google => web graph
    -- LinkedIn, E-bay, Amazon, etc.
    -- hetionet, Biograph, ReactomeDB, covidgraph, covid-net, Science Forum, etc. 

Graph theory was pioneered by Euler in the 18th cen‐ tury, and has been actively researched and improved by mathematicians, sociologists, anthropologists, and other practitioners ever since.

## What is a graph? 

==> A graph is a collection of vertices (nodes) and edges (relationships) that connect them.
 
 An example of graphs and relationships : Twitter-like graph :

 ![](/path/to/fig2a)


 `node label : USER`

 `relationships : semantic context (who follows who)`

Extension of Ruth's messages : `CURRENT : last message` & `PREVIOUS : twitter timeline`.

This is a Labelled property graph model. 
 A labeled property graph has the following characteristics :

        - It contains nodes and relationships. 
        - Nodes contain properties (key-value pairs). 
        - Nodes can be labeled with one or more labels.
        - Relationships are named and directed, and
         always have a start and end node. 
        - Relationships can also contain properties.


Graph databases : 

A graph database is an online, operational database management system with Create, Read, Update, and Delete (CRUD) methods that expose a graph data model. Graph databases are generally built for use with transactional (OLTP) systems.

The underlying storage Some graph databases use native graph storage, which is optimized and designed for storing and managing graphs. Not all graph database technologies use native graph storage, however. Some serialize the graph data into a relational database, object-oriented database, or other types of NOSQL stores.
The processing engine
Some definitions of graph databases require that they be capable of index-free adjacency, meaning that connected nodes physically “point” to each other in the database.8
Here we take a slightly broader view. Any database that from the user’s
perspective behaves like a graph database (i.e., exposes a graph data model through CRUD operations), qualifies as a graph database. We do acknowledge, however, the significant performance advantages of index-free adjacency, and therefore use the term native graph processing in reference to graph databases that leverage index-free adjacency.
****
||[home](https://whitelabgx.github.io/home/)||



