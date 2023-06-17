# Isc563-spring2023 [Dominic Colter]
# Template adopted from Cornell University Library

GENERAL INFORMATION

Title of Dataset: DrugAge Build 4

Date of data collection: November 20, 2021

Geographic location of data collection: University of Liverpool, UK


SHARING/ACCESS INFORMATION

Licenses/restrictions placed on the data: Creative Commons Attribution 3.0 Unported License.

Links to publications that cite or use the data: https://pubmed.ncbi.nlm.nih.gov/28299908/ , https://pubmed.ncbi.nlm.nih.gov/37032369/ , https://pubmed.ncbi.nlm.nih.gov/36806357/ , https://pubmed.ncbi.nlm.nih.gov/28155715/

Links to other publicly accessible locations of the data: https://genomics.senescence.info/drugs/

Was data derived from another source?
If yes, list source(s): Data was manually curated from 324 publications on PudMed. PubMed IDs are listed in the dataset.

Recommended citation for this dataset: 

Barardo, D., Thornton, D., Thoppil, H., Walsh, M., Sharifi, S., Ferreira, S., Anzic, A., Fernandes, M., Monteiro, P., Grum, T., Cordeiro, R., De-Souza, E.A., Budovsky, A., Araujo, N., Gruber, J., Petrascheck, M., Fraifeld, V.E., Zhavoronkov, A., Moskalev, A., de Magalhaes, J.P. (2017) "The DrugAge database of ageing-related drugs." Aging Cell 16(3):594-597


DATA & FILE OVERVIEW

File List: drugage.csv


METHODOLOGICAL INFORMATION

Description of methods used for collection/generation of data (From citation listed): 

"Data were primarily assembled using literature searches (see Experimental Procedures in the Supporting information). Additionally, we used other databases and submissions from the scientific community, resulting in 324 research articles. DrugAge data focus solely on assays performed in standard conditions (Experimental Procedures in Supporting information). Only compounds, drugs and substances extending lifespan in a statistically significant manner in at least one experiment were included, but conflicting and negative results were then also added to those entries to provide a balanced literature survey."

"The literature mining for DrugAge came from three sources: data submitted by the scientific community; mining of pre-existing aging-related databases; and PubMed queries. The existing databases queried were: AgeFactDB, Geroprotectors.org, and the Aging Genes and Interventions Database."

"To be a candidate for inclusion in DrugAge, a molecule or substance (e.g. whole apple extract) must extend lifespan (average, median or maximum), reaching statistical significance in at least one lifespan assay in one model organism. All literature mined was manually curated and subjected to quality control in order to standardize compound naming conventions, species, and strains. "

Barardo, D., Thornton, D., Thoppil, H., Walsh, M., Sharifi, S., Ferreira, S., Anzic, A., Fernandes, M., Monteiro, P., Grum, T., Cordeiro, R., De-Souza, E.A., Budovsky, A., Araujo, N., Gruber, J., Petrascheck, M., Fraifeld, V.E., Zhavoronkov, A., Moskalev, A., de Magalhaes, J.P. (2017) "The DrugAge database of ageing-related drugs." Aging Cell 16(3):594-597


DATA-SPECIFIC INFORMATION FOR: drugage.csv

Number of variables: 12

Number of cases/rows: 3,265

Variable List:
  1. compound_name
    - Compound used for a particular study. This was treated as a qualitative variable.
    
  2. cas_number
   - Numerical identifier for a parituclar chemical compound. This was treated as a qualitative variable.
   
  3. species
   - Species name for a particular study. This was treated as a qualitative variable.
   
  4. strain
   - The strain of the species used in a particular study. This was treated as a qualitative variable.
   
  5. dosage
    - The dosage of a particular compound used in a study. The units varied across all enteries. This was treated as a qualitative variable.
    
  6. avg_lifespan_change
    - The average lifespan change observed with a particular compound. Measured as a percentage. This was treated as a quantitative variable.
    
  7. max_lifespan_change
    - The max lifespan change observed with a particular compound. Measured as a percentage. This was treated as a quantitative variable.
    
  8. gender
    - Gender of a particular organism used in a study. This was treated as a qualitative variable.
    
  9. significance
    - significance of the study (ND = not determined, NS = not significant, S = significant). This was treated as a qualitative variable.
    
  10. pubmed_id
    - The PubMed ID number for a particular study. This was treated as a qualitative variable.
    
  11. Blank column
  
  12. Blank column
  