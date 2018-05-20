# BPMN2OWL
This program stores BPMN Diagrams into an Ontolgy of the BPMN Standard. It was part of a Bachelor Thesis at FH Joanneum in student program "Informationsmanagement". The thesis is called "Speichern von BPMN Diagrammen in Ontologien" which german for storage of BPMN diagrams in ontologies and is can be found in the **thesis** folder.

As Input parameters you need:

- A BPMN Diagram
- An Ontology of the BPMN Standard, find one attached in the **ontology** folder

# Function
In order to use this software clone or download to a local directory. Afterwards use:
```sh
java -jar BPMN2OWL.jar BPMN-Path OWL-Path
```
As owl use the ontology in the **ontology** folder.
Java Version used "9.0.4" with Java(TM) SE Runtime Environment (build 9.0.4+11).

# Adaption
In case any addtions need to be made, there are 3 classes available in this project. These are located at **classes --> at.fh.joanneum.bac2**
The first one is BPMNReader.class, which is used to read bpmn files.
OWLExchange.class is used to read the ontology and adapt it. Therefore most adaptions will have to be done in this class. 
BPMN2OWL is used to getElements from BPMNReader and provide it for OWLExchange.
This project was built with maven version 3.3.9.
To make any adaptions, unpack the dependencies with maven and include it into an IDE like Eclipse. 

# Author
All work was done by Nikolaus Hribernig and Supervised by FH-Prof. Mag. Dr.Robert Singer.

