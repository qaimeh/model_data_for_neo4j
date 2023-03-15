# model_data_for_neo4j
This test create parse Uniprot XML data and model it for neo4j

# how to run the code
1) Install neo4j on you local machine, you can use docker to run with following commands:
 ```
  docker run \
  --publish=7474:7474 \
  --publish=7687:7687 \
  --volume=$HOME/neo4j/data:/data \
  --env NEO4J_AUTH=neo4j/neo4j123   neo4j
 ```
2) In Jupyter copy and paste the code from file "Uniprot_XML_to_Neo4j.ipynb" and execute. This code will transform the XML data from file "uniprot.xml"  into neo4j property graph model. execute the CYPHER query and fetch the required results.


# Example: data model
![Alt text](https://github.com/qaimeh/model_data_for_neo4j/blob/main/example_data_model.png "Optional title")

