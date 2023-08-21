# LiveStockHealthOntologyWp1
### [![DOI](https://zenodo.org/badge/659116364.svg)](https://zenodo.org/badge/latestdoi/659116364)

1: Create a standardized FAIR guideline framework that balances data requirements, accessibility, availability, connectivity, and value generation.

2: Design a Livestock Health Ontology (LHO) tailored to specific species, enriching knowledge graphs with domain expertise.

3: Convert raw cattle data into RDF format, harnessing RDF benefits for improved data sharing, integration, and querying.

4:Create a mapping process to match the cleaned RDF data with the species-specific LHO ontology, ensuring that the data can work together smoothly and be easily understood. You can find the code in R, PySpark, and Python notebooks here.

5: Implement a data visualization tool to analyze and report farm animal disease management data, empowering insightful decision-making and data interpretation.

We've made CattleUse work on three platforms: Python, R, and Pyspark. We did this by using data from different animal health service labs in Europe: DGZ, GD, Pathosen, Ireland, and ARSIA. Specifically, the DGZ lab's data works on all three platforms.
For ARSIA, PAthosen, Ireland, and GD labs:

. We used Panda in Python and R to implement the ARSIA lab's data.

. Similarly, we used Panda in Python and R for the Pathosen lab's data.

. The Ireland lab's data also works using the Panda library in both Python and R.

. Lastly, the GD lab's data is functional with Panda in both Python and R.

In summary, while the Pyspark implementation was showcased with the DGZ dataset, the same methodology was followed for the remaining datasets (GD, Pathosen, ARSIA, and Ireland), albeit without a separate Pyspark demonstration. In the 'UnionOfAllRDF.ipynb' notebook, we aggregate RDF data from DGZ, Pathosen, Ireland, GD, and ARSIA Labs. This process involves combining RDF files from these sources into a unified representation. The resulting unified RDF representation is then utilized in visualization tools for example Tableau for comprehensive analysis.

| Platforms         |          DGZ             |	     GD             |	      Pathosen	            |      Ireland           |	    Arsia              |
| ------------------| -------------------------| -------------------- |-----------------------------| -----------------------| ------------------------|
| Python Panda      | [DGZDataPandacode.ipynb ](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/DGZDataPandacode.ipynb) | [GDDataPandaCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/GDDataPandaCode.ipynb)  |[PathosenDataPandaCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/PathosenDataPandaCode.ipyn) |[IrelandPandacode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/IrelandPandacode.ipynb)| [ARSIADataPandaCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/ARSIADataPandaCode.ipynb)|
| R                 | [DGZDataRacode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/DGZDataRCode.ipynb)      | [GDDataRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/GDDataRCode.ipynb)    | [PathosenDataRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/PathosenDataRCode.ipynb)     | [IrelandRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/IrelandDataRCode.ipyn)     | [ARSIADataRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/ARSIADataRCode.ipynb)    |
| PySpark           | [DGZDataPysparkcode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/DGZDataPysparkCode.ipynb) |----------------------|-----------------------------| -----------------------| ------------------------|
| Union of All RDF  | -------------------------|-UnionOfAllRDF.ipynb--|-----------------------------|------------------------|-------------------------|




