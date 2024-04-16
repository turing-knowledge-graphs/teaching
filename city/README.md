## Semantic Web Technologies and Knowledge Graphs (SWT&KG)

Module leader: [Ernesto Jimenez-Ruiz](https://www.city.ac.uk/about/people/academics/ernesto-jimenez-ruiz)

### Academic year 2023-2024: 

Module delivered to UG students in [Computer Science](https://www.city.ac.uk/prospective-students/courses/undergraduate/computer-science) (IN3067) and MSc students (INM713) in [Data Science](https://www.city.ac.uk/prospective-students/courses/postgraduate/data-science) and [Software Engineering with Cloud Computing](https://www.city.ac.uk/prospective-students/courses/postgraduate/software-engineering) at City, University of London.

Suggested [reading list](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/ReadingList.md).

Recordings of the lectures available [here](https://drive.google.com/drive/folders/1RYVjf6nauHCsgdnReE-ziLbHVqGu0W2m?usp=sharing).

#### Lectures

1. Introduction: Becoming a Knowledge Scientist. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture1_Introduction_Knowledge_Scientist_slides_2024.pdf). [Report](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture1_Introduction_Knowledge_Scientist_report_2024.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session1_Infrastructure_2024.pdf).
2. RDF-based Knowledge Graphs. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture2_RDF_Knowledge_Graphs_slides_2024.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session2_RDF_2024_with_solutions.pdf).
3. OWL Ontology Language. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture3_OWL_Language_slides_2024.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session3_OWL.pdf). [Pizza OWL Tutorial](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/)
4. SPARQL Query Language. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture4_SPARQL_Query_Language_1.0_slides_2024.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session4_SPARQL1_with_solutions.pdf).
5. From Tabular Data to Knowledge Graphs. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture5_Tabular_to_KG_2024_slides.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session5_CSV2KG_with_solutions.pdf).
6. RDFS Semantics and OWL 2 Profiles. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture6_RDFS_OWL2Profiles_2024_slides.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session6_RDFS_OWL2RL_2024_with_solutions.pdf).
7. SPARQL 1.1, Rules and Graph Database solutions. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture7_SPARQL1.1_Rules_GraphDatabases_2024_slides.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session7_SPARQL1.1_GraphDB_2024_with_solutions.pdf).
8. Ontology (Knowledge Graph) Alignment. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture8_Ontology_Alignment_2024_slides.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session8_KGAlignment_2024.pdf).
9. Ontology (Knowledge Graph) Embeddings. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture9_OntologyEmbeddings_2024_slides.pdf). [Laboratory](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lab_Session9_OWL2Vec-Star.pdf).
10. Knowledge Graphs and Language Models. [Slides](https://github.com/turing-knowledge-graphs/teaching/blob/main/city/2023-2024/IN3067-INM713_Lecture10_KGs-LLMs_2024_slides.pdf). [Laboratory](https://github.com/KRR-Oxford/DeepOnto)  (optional: exploring the DeepOnto library).

#### Labs with solutions (python and java): 
- [https://github.com/city-knowledge-graphs](https://github.com/city-knowledge-graphs)
- Main libraries: 
  - ***Java***: [Jena](https://jena.apache.org/index.html): complete library to create RDF triples, execute SPARQL queries, access ontology data, perform RDFS and OWL reasoning (although not built-in OWL 2 reasoning).
  - ***Python***: [Owlready2](https://pypi.org/project/Owlready2/) (good option to access an already created ontology), [SPARQLWrapper](https://pypi.org/project/SPARQLWrapper/) (connection to an SPARQL Endpoint), [RDFlib](https://pypi.org/project/rdflib/) (manipulation and access of local RDF graphs), [OWL-RL](https://pypi.org/project/owlrl/5.2.1/) (very easy to expand and RDF graph with RDFS or OWL 2 RL entailments), [OWL2Vec*](https://github.com/KRR-Oxford/OWL2Vec-Star) (entity and lexical embeddings from OWL 2 ontologies).
- [Protége](https://protege.stanford.edu/) is used as ontology editor.
- Coursework: [description and datasets](https://drive.google.com/drive/folders/1WlINYleyUdV-rQst8qqBefiixwv9yGvR?usp=sharing).


#### Datasets 
- [Pizza ontology](https://protege.stanford.edu/ontologies/pizza/pizza.owl)
- [SPARQL Playground](http://sparql-playground.sib.swiss/)
- [Nobel prize data](https://www.nobelprize.org/about/linked-data-examples/)
- [World cities dataset](https://simplemaps.com/data/world-cities)
- [DBPedia](https://dbpedia.org/sparql)
- [OAEI datasets](http://oaei.ontologymatching.org/) (ontology alignment)


---

<img src="city-logo.jpg" width="60" alt="City">   [City, University of London](https://www.city.ac.uk/)

