## Forest Observatory Ontology Knowledge Graph (FOO-KG)

[FOO-KG](https://naeima.github.io/fooKG/) is a wildlife knowledge graph dataset used for poaching prediction. As shown in the figure below, it was constructed by populating the Forest Observatory Ontology [FOO](https://w3id.org/def/foo#) with RDF wildlife datasets generated by sensors [website](https://ontology.forest-observatory.org). This was achieved by mapping each data table to the sensor class, each column to a property or predicate, each row to an instance or individual of the class sensor, and each cell to a literal using [YARRML](https://rml.io/yarrrml/), a human-readable text-based representation for declarative Linked Data generation rules. The output RDF graphs are then fed into a graph database and merged with FOO to form an ontology-based knowledge graph.

![image](https://lucid.app/publicSegments/view/5eec075d-5ace-4ec0-8165-85ea232301a2/image.png)


## FOO-KG (a) Jupyter Notebook

This Jupyter notebook, titled "FOO-KG (a)", is designed for processing and analysing RDF (Resource Description Framework) data. The notebook focuses on loading RDF data, querying it using SPARQL, extracting features and labels, and preparing the data for further analysis or predictive modelling. This notebook is particularly useful for those working with geospatial RDF data and looking to predict elephants' geolocation.

## Requirements

To run this notebook, you will need the following:

- Python 3.x
- Jupyter Notebook or Jupyter Lab environment
- The following Python libraries:
  - `rdflib` for handling RDF data
  - `numpy` and `pandas` for data manipulation
  - `tensorflow` and `sklearn` for machine learning tasks
  - `networkx` for network analysis (if applicable)
  - Other dependencies as required by the code (refer to the first cell of the notebook for all imports)

## Setup

1. **Install Python and Jupyter**: Ensure you have Python 3.x installed along with Jupyter Notebook or Jupyter Lab.

2. **Clone/Download the Notebook**: Obtain a copy of the "FOO-KG (a)" notebook onto your local machine.

3. **Install Required Libraries**: You can install the required libraries using pip. For example:

   ```
   pip install rdflib numpy pandas tensorflow sklearn networkx
   ```

4. **Download RDF Data**: Ensure you have the RDF data file (e.g., "SeriKG.rdf") available and in the correct format as expected by the notebook.

## Usage

1. **Open the Notebook**: Open the "FOO-KG (a)" notebook in your Jupyter environment.

2. **Run Each Cell**: Execute each cell sequentially. The initial cells import necessary libraries and define functions.

3. **Load and Query RDF Data**: The notebook will load RDF data from a file and perform a SPARQL query to extract relevant features and labels.

4. **Data Analysis and Modeling**: Follow the subsequent cells for data preprocessing, analysis, and potentially building machine learning models.
   
5. The dataset is available upon request.

## Additional Notes

- The notebook assumes some familiarity with RDF data, SPARQL queries, and Python programming.
- You may need to modify the SPARQL query and data paths according to your specific RDF dataset.
- Ensure that all dependencies are correctly installed and imported in the notebook.
