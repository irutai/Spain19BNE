# Spain19BNE
A dataset containing approximately 12,000 documents in Spanish, written by 559 different authors, with their original manifestations held in the BNE collection from the XIX century and a set of relevant judgments.

The contents of the files are:

#### Spain19BNE.zip

This file contains the OCR-extracted text of the documents in the collection.

The dataset is organized into **559 directories**, each one representing an author in the **Spain19BNE** collection.  
Inside each author directory, you will find the `.txt` files corresponding to each **manifestation** of that author included in the collection.

Each text file follows this naming convention:

`publication_code_publication_year_author_name.txt`

#### Example


Zorrilla_José_1817-1893:
|__ bimo0001594704_1839_Zorrilla_José_1817-1893.txt
|__ bimo0001594627_1910_Zorrilla_José_1817-1893.txt


#### BNE_judgments_all.csv 

This file contains a total of 597 validated whole–whole relationships (WW). These judgments are bases on a set of uniform title heading provided by the BNE. The format of each judments is: 

author;	code1;	code2;	label

#### Example
García_Lorca_Federico_1898-1936;bimo0000902803;bimo0000902810;WW
 

#### BNE_judgments_0.1.csv 

This file contains a subset of the previous files, containing only those relationships where the quality of the documents is greater or equal that 0.1. The total number of relationships in the file is 562

 
#### system_based_judgement.csv

Fhis files contains a total of manually evaluated relationships in the coleccion. The instances are distributed as 233 whole–whole (WW), 85 whole–part (WP), and 49 part–part (PP)instances. The format is the same than previous ones, but the label indicating the relationships can be WW, WP or PP

 
 


## License
This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

### Attribution Requirement
If you use, modify, or distribute this work, you must give appropriate credit by citing the following paper:

Luis M. de Campos, Juan M. Fernández-Luna, Juan F. Huete and Elena Sánchez-Nogales. Determining Whole-Part Relationships when Cataloging 19th Century Monographs. Submitted to Digital Scholarship in the Humanities, 2026.
DOI: https://doi.org/xxxxx

In addition, you must indicate if changes were made and include a link to this repository.
