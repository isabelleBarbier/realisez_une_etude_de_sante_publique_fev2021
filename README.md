

# Réalisez une étude de santé publique 
# Conduct a public health survey

<img src="https://user-images.githubusercontent.com/47240631/152846262-a8eb5986-cd91-4f56-bad1-cc0f32b83d89.jpg" width=1000 height=500>

## Description projet
Based on data retrieved from the FAO website, the project is a statistical study to define the different causes of hunger in the world.

## Installation
- language : `Python (version 3)`
- [Installation Anaconda](https://www.anaconda.com/products/individual)
- Conda Packages :   
  - `Notebook jupyter`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `sqlite3`
  - `csv`  

## Files's description
- FAO_etude_sante_publique_reponses_ P3.ipynb : principal analysis file
- FAO_BDD_py_cvs_FAO_avecImportCsv.ipynb : creation of the DB "py_cvs_FAO.db" and the tables (creation of tables with data filling from the line-by-line reading of csv files) 
- FAO_creationFichiers_csv.ipynb : creation of csv files for the future FAO database
- FAO_requete_try_exept.ipynb : request SQL file
- pyFAO_BDD_requeteSql.ipynb : this database is used for queries with SQLiteSudio by using 'read_sql_query()' for queries (advantage: no cursor object creation, no fetchall, and     creation of a dataframe for data presentation)

## Data files
- fr_animaux.csv : multiple animal product production indicators in 2013
- fr_population.csv: world population by country in 2013
- fr_vegetaux.csv: multiple crop product production indicators in 2013
- fr_céréales.csv: quantity of cereals produced worldwide in 2013 
- fr_sousalimentation.csv: number of undernourished people in the world from 2013 to 2017

## Presentation slides
- P3_04_presentation_etudeSantePublique.pdf : survey's summary (PDF)
- pyFAO_BDD_requeteSql.ipynb : request's results (PDF)

