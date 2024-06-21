# Primary-Health-Care-Appointments-and-Hospital-Stay-An-Impact-Analysis

**Grupo composto por:**
- [Joana Lopes](https://github.com/joanalopes0711) (pg53498)
- [Tiago Miranda](https://github.com/tiagomiranda24) (pg54437)

<div align="justify">
This practical work was developed in an academic context, in the curricular unit of “Intelligent Analysis in BigData Systems”, of the Master´s degree in Bioinformatics, and the main objetive was to understand whether the number of consultations given in primary health care has a direct impact on the number of hospitalizations, providing important insights into the functioning of the Portuguese healthcare system.

**Workflow**

This work followed ETL (Extract-Transform-Load) principles. First of all we extract two datasets to make this analysis.Both datasets were extracted directly from reliable sources, namely certified websites such as the Portuguese Public Administration's open data portal (dados.gov) and 
the “Transparency” area of the Portuguese National Health Service (“Sistema Nacional de Saude” - SNS) website, an Open Data initiative carried out by the Ministry of Health, in order to make available the vast set of data that underlie the operations and transactions that take place within the scope of the SNS's activities. 
To manipulate our data, we used the Pandas library in Python, which allowed us to efficiently transform the data and prepare it for analysis. After this we join the datasets using pandas and pyspark to test test which of the two would be faster.
At the end we load our data in mongoDB and make a connection with PowerBI, trought a ODBC driver, to create powerfull dashboards to visulize and produce insights of our data.

**Contents**

In this respositorium you can found the datasets, the jupyter notebook, the final article and the dashboards. All of this materials were revised by the teachers of the curricular unit.
