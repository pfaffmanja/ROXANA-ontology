# ROXANA-ontology  
**R**eference **O**ntology for E**X**pert bound processes in M**ANA**fcturing

An ontology for representing expert-bound processes in manufacturing. 

## Introduction and Scope of ROXANA
The difficulty with predominantly manual activities lies in the individuality of the processes, the products and the resulting lack of standardization. Only a few employees in the companies concerned can carry out the operations. It is not uncommon for employees to remain in the companies for a very long time, gaining valuable experience and building up knowledge over the years. This knowledge can rightly be called the most valuable resource. Existing public ontologies still lack adequate representation of expert knowledge. These ontologies describe known and usually often recurring facts. These include, for example, manufacturing techniques, material properties, product requirements or strategies (such as maintenance).  
Adaptive, changing processes are characterized by their primary individual character and generally require processing by experts. Experts are characterized by their ability to transfer experience to new, unfamiliar situations by abstracting general knowledge and recognizing semantic similarities. This often implicit knowledge, also known as intuition, is bound to the knowledge carrier and is not usually directly accessible or verbalizable. A knowledge model needs to be designed which describes activities in detail, including the associated process dependencies, but which can be extended adaptively and situation-specifically to include work activities.

## Guide for modeling
For more information and examples on how to use ROXANA, please see the [Wiki](https://github.com/pfaffmanja/ROXANA-ontology/wiki).

## Reuse existing Ontologiesv / Interoperability
### Top-Level Ontology

For portability and interoperability, ROXANA uses the [BFO](https://basic-formal-ontology.org/) as a top-level ontology. The Industrial Ontology Foundry ([IOF](https://www.industrialontologies.org/)), a community developing an ontology for the production and industry domain, also uses the BFO. Like IOF, ROXANA has a focus on the manufacturing industry.

### Common Core Ontologies
ROXANA direct imports the following Common Core Ontologies:
- Event Ontology
- Units of Measure Ontology

The following ontologies will be imported as indirected imports:
- Information Entity Ontology
- bfo
- RO
- Extended Relation Ontology
- Geospatial Ontology
- Time Ontology
- Extended Relation Ontology

The Artefact Ontology (CCO) was also used in part. For better clarity, however, individual domain-relevant concepts were implemented and further specified directly in ROXANA. New concepts were also added as rdfs:subClassOf of cco:Artifact. 

For more information regarding these specific mid-level extensions of the BFO, please see their [Github Repository](https://github.com/CommonCoreOntology/CommonCoreOntologies). 

## Releases
- ROXANA 1.0 Initial Version 12/2022

## Contributing and developing
Hints and suggestions are always welcome. The ontology was part of a research and development project. It was tested and evaluated for the commissioning of special production machines for three different small and medium sized companies. 
Everyone can initiate a discussion via a ticket. A wiki with hints on how to proceed will follow soon. 
