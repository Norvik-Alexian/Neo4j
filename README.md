# Neo4j

Neo4j is the world’s leading graph database. The architecture is designed for optimal management, storage, 
and traversal of nodes and relationships. 
The graph database takes a property graph approach, which is beneficial for both traversal performance and operations runtime.

## Cypher

Cypher is Neo4j’s graph query language that allows users to store and retrieve data from the graph database. 
It is a declarative, SQL-inspired language for describing visual patterns in graphs using ASCII-art syntax. 
The syntax provides a visual and logical way to match patterns of nodes and relationships in the graph. 
Cypher has been designed to be easy to learn, understand, and use for everyone, but also incorporate the power and functionality of other standard data access languages.

## What is a Graph Database
A graph database stores nodes and relationships instead of tables, or documents.
Data is stored just like you might sketch ideas on a whiteboard. 
Your data is stored without restricting it to a pre-defined model, allowing a very flexible way of thinking about and using it.

Modern data problems often involve many-to-many relationships with heterogeneous data that sets up needs to:
* Navigate deep hierarchies
* Find hidden connections between distant items
* Discover inter-relationships between items

## The property graph model
In Neo4j, information is organized as nodes, relationships, and properties.

Nodes are the entities in the graph:
* Nodes can be tagged with labels, representing their different roles in your domain. (For example, Person).
* Nodes can hold any number of key-value pairs, or properties. (For example, name)
* Node labels may also attach metadata (such as index or constraint information) to certain nodes.

Relationships provide directed, named, connections between two node entities (e.g. Person LOVES Person).

* Relationships always have a direction, a type, a start node, and an end node, and they can have properties, just like nodes.
* Nodes can have any number or type of relationships without sacrificing performance.
* Although relationships are always directed, they can be navigated efficiently in any direction.
