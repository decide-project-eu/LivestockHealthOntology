# LiveStockHealthOntologyWp1
1: Create a standardized FAIR guideline framework that balances data requirements, accessibility, availability, connectivity, and value generation.

2: Design a Livestock Health Ontology (LHO) tailored to specific species, enriching knowledge graphs with domain expertise.

3: Convert raw cattle data into RDF format, harnessing RDF benefits for improved data sharing, integration, and querying.

4:Create a mapping process to match the cleaned RDF data with the species-specific LHO ontology, ensuring that the data can work together smoothly and be easily understood. You can find the code in R, PySpark, and Python notebooks here.

5: Implement a data visualization tool to analyze and report farm animal disease management data, empowering insightful decision-making and data interpretation.

We've made CattleUse work on three platforms: Python, R, and Pyspark. We did this by using data from different animal health service labs in Europe: DGZ, GD, Pathosen, Ireland, and ARSIA. Specifically, the DGZ lab's data works on all three platforms.
For each lab:
. We used Panda in Python and R to implement the ARSIA lab's data.
. Similarly, we used Panda in Python and R for the Pathosen lab's data.
. The Ireland lab's data also works using the Panda library in both Python and R.
. Lastly, the GD lab's data is functional with Panda in both Python and R.
In summary, while the Pyspark implementation was showcased with the DGZ dataset, the same methodology was followed for the remaining datasets (GD, Pathosen, ARSIA, and Ireland), albeit without a separate Pyspark demonstration.

| Platforms         |          DGZ             |	     GD             |	      Pathosen	            |      Ireland           |	    Arsia              |
| ------------------| -------------------------| -------------------- |-----------------------------| -----------------------| ------------------------|
| Python Panda      | DGZDataPandacode.ipynb   | GDDataPandaCode.ipynb| PathosenDataPandaCode.ipynb | IrelandPandacode.ipynb | ARSIADataPandaCode.ipynb|
| R                 | DGZDataRacode.ipynb      | GDDataRCode.ipynb    | PathosenDataRCode.ipynb     | IrelandRCode.ipynb     | ARSIADataRCode.ipynb    |
| PySpark           | DGZDataPysparkcode.ipynb |----------------------|-----------------------------| -----------------------| ------------------------|
