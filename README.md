# rdf-mmdb
RDF project for [MolMeDB](https://molmedb.upol.cz/). This repository was founded for purpose of my thesis on incerasing interoparability of MolMeDB database.

* Shex files contain schema for data model.

* Turtle files contain R2RML mappings and membranes_to_CHEBI.ttl is file with links between membranes and their membrane components in CHEBI database.

* Temporary vocabulary is stored in temp.rdfs file.



## RDF data model

Original SQL schema of MolMeDB.

![alt text](https://github.com/DominikMartinat/rdf-mmdb/blob/master/diagrams/schema-mmdb.png)

Substances.

![alt text](https://github.com/DominikMartinat/rdf-mmdb/blob/master/diagrams/diagram-substances.png)

Membrane interactions.

![alt text](https://github.com/DominikMartinat/rdf-mmdb/blob/master/diagrams/diagram-new-interaction.png)

Transporter interactions.

![alt text](https://github.com/DominikMartinat/rdf-mmdb/blob/master/diagrams/diagram-new-transporter.png)

Publications. This one will be simplified.

![alt text](https://github.com/DominikMartinat/rdf-mmdb/blob/master/diagrams/diagram-publications.png)
