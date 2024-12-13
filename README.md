## PoachNet: Predict Poaching with ontology-based Knowledge Graph

[FOO-KG](https://naeima.github.io/fooKG/) is a wildlife knowledge graph dataset used for poaching prediction. As shown in the figure below, it was constructed by populating the Forest Observatory Ontology [FOO](https://w3id.org/def/foo#) with RDF wildlife datasets generated by sensors [website](https://ontology.forest-observatory.org). This was achieved by mapping each data table to the sensor class, each column to a property or predicate, each row to an instance or individual of the class sensor, and each cell to a literal using [YARRML](https://rml.io/yarrrml/), a human-readable text-based representation for declarative Linked Data generation rules. The output RDF graphs are then fed into a graph database and merged with FOO to form an ontology-based knowledge graph.

![image](https://github.com/Naeima/PoachNet/blob/ed7689e9128f9bf37cf51e5cdf7bc5c70d86e07e/KGBuild.png)


## PoachNet 

This Jupyter notebook is designed for processing and analysing RDF (Resource Description Framework) data. The notebook focuses on loading RDF data, querying it using SPARQL, extracting features and labels, and preparing the data for further analysis or predictive modelling. This notebook is particularly useful for those working with geospatial RDF data and looking to predict elephants' geolocation. 

# PoachNet code: [Click here](https://github.com/Naeima/PoachNet/blob/e21c46c0698c39fa626096ab650d506716c1682d/PoachNet.ipynb)


![image](https://github.com/Naeima/PoachNet/blob/6416298db13ed86751840e0a68ded5f63cf3179c/PoachNet.png)

# Query elephant Seri query

![image](https://github.com/Naeima/PoachNet/blob/f59fba205a473eaeb19f24192fc45e38c5db0dd3/SelectSeri.png)

# Insert Semantic Web Rule Language (SWRL) 


# Query poaching 



# Evaluation code: [Click here](https://github.com/Naeima/PoachNet/blob/bb4af1077d988d686796be60e0680154e02c244c/Linear_Regression%2C_Polynomial_and_VAR.ipynb)
