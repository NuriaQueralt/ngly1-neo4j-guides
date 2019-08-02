# NGLY1 GRAPH NEO4J GUIDES

This is the project to develop the user guide in the Neo4j Browser of the NGLY1 Deficiency Knowledge Graph.


#### Prerequisites

Python 3


## HOW TO CREATE THE GUIDES
1. To create the asciidoc or .adoc document open an editor and start to edit:

```bash
vim adoc/index.adoc
```

2. To create the html guides run:

```bash
./run.sh adoc/index.adoc guides/index.html 
```

3. To start the HTTP server run:

```bash
python3 http-server.py &
```

For more information the user should refere to [the Neo4j guidelines](https://github.com/neo4j-contrib/neo4j-guides).
