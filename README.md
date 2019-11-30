# Data Science Ontology

[![Build Status](https://travis-ci.org/IBM/datascienceontology.svg?branch=master)](https://travis-ci.org/IBM/datascienceontology) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1401676.svg)](https://doi.org/10.5281/zenodo.1401676)

The [Data Science Ontology](https://www.datascienceontology.org/) is a knowledge
base about data science that aims to:

- catalog and formalize the concepts of data science
- semantically annotate popular software packages for data science
- power new AI assistants for data scientists

To learn more about the Data Science Ontology,
[start here](https://www.datascienceontology.org/help).

The Data Science Ontology is young but growing! We welcome contributions of 
concepts and annotations.
[Learn how to contribute](https://www.datascienceontology.org/help/contribute).
For improvements to the web frontend, please visit the dedicated frontend
[repository](https://github.com/IBM/datascienceontology-frontend).

## Getting started on your machine

Ensure `jq`, `pandoc-citeproc`, and `yarn` are installed.

To install the JavaScript-based dependencies: `yarn`

To build the ontology into the `build` folder: `npm run build`

To validate the ontology after building: `npm run validate`
