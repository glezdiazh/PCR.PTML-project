# PCR.PTML-project

# PCR.PTML Artificial Intelligence-Eperimental Microbiome Analysis: Applications to Ancient DNA and Tree Soil Metagenomics Cases of Study.

# Authors 
Jose L. Rodriguez.a#, Estefania Ascencio.b,c,d,e#, Jose M. Ageitos a, Lucia Feijoo a, Shan He b,c,e Amirreza Daghighi b,c, Gerardo Casanola b, Cristian R. Munteanu d, Santiago Rodriguez Yañezd*, Alejandro Pazosd, Harbil Bediagae Brenda Duran Ordialesf Raquel Estebanf,Ana-Maria Heres gh, Jorge Curiel Yusteg l, Lur Epeldei, Bakhtiyor Rasulev b,cTomas Gonzaleza ,Sonia Arrasate j, and Humberto  González j,k,,l *   


# Affiliations 
aDepartment of Microbiology and Parasitology, Faculty of Pharmacy, University of Santiago de Compostela, 15782, Santiago de Compostela, Spain.
b Department of Coatings and Polymeric Materials, North Dakota State University, 
58102, Fargo, North Dakota, United States.
c Biomedical Engineering Program, North Dakota State University, Fargo, ND 58102, USA.
d Department of Information and Communication Technologies, Computer Science Faculty, University of Coruña (UDC), 15071, A Coruña, Spain.
e IKERDATA S.L., ZITEK, University of Basque Country UPVEHU, 
Rectorate Building, 48940 Leioa, Spain.
fDepartment of Plant Biology and Ecology, University of Basque Country (UPV/EHU), Leioa, Bizkaia, 
gBC3-Basque Centre for Climate Change, Scientific Campus of the University of the Basque Country, Leioa, Bizkaia, Spain.
h Department of Forest Engineering, Forest Management Planning and Terrestrial Measurements, Faculty of Silviculture and Forest Engineering, Transilvania University of Braşov, Sirul Beethoven -1, 500123 Braşov, Romania iDepartment of Conservation of Natural Resources, NEIKERBasque Institute for Agricultural Research and Development, Basque Research and Technology Alliance (BRTA) Bizkaia Science and Technology Park, Derio, Spain.
jDepartment of Organic and Inorganic Chemistry and Basque Center for Biophysics;
University of Basque Country (UPV/EHU), 48940, Leioa, Basque Country, Spain.
k BIOFISIKA Institute, Spanish National Research Council (CSIC) -  University of the Basque Country (UPV/EHU), 48940, Leioa, Basque Country, Spain.
l IKERBASQUE, Basque Foundation for Science, 48011, Bilbao, Biscay, Spain.




# Abstract. 
The exponential growth of genomic data has created a pressing need for methods capable of interpreting complex biological information, especially in fields like paleogenomics and environmental metagenomics. Ancient DNA (aDNA) analysis faces challenges such as degradation and contamination, while soil metagenomic DNA (soDNA) analysis is hindered by microbial diversity and incomplete reference databases. To address these limitations, this study proposes the PCR.PTML methodology, which integrates machine learning with Perturbation Theory to analyze genetic sequences without the need for alignment.
Two models were developed: the first classifies bacterial aDNA sequences extracted from Miocene amber; the second predicts tree health using microbial gene abundance in forest soils. Both rely on entropy-based descriptors (θₖ) and structural differences (Δθₖ) between query and reference sequences, which serve as perturbation operators for supervised learning algorithms. This approach allows the detection of meaningful patterns even without complete genomic references.
The aDNA model achieved 84.2% sensitivity and 83.6% specificity, while the soDNA model using Random Forest reached 98.49% sensitivity and 83.21% specificity. These results confirm the robustness and applicability of PCR.PTML in diverse genomic contexts, presenting it as a valuable tool for ancient DNA classification and environmental metagenomics analysis.


# Keywords
Ancient DNA Sequences, Perturbation Theory, Machine Learning, Shannon’s Information Theory.

# Authors Contributions

José L.R. Rama, José Manuel Ageitos, Lucía Feijoo-Siota, and Tomás G. Villa: DNA isolation, sequencing, alignment, annotation, manuscript writing and figure preparation.
Estefanía Ascencio-Medina, Amirreza Daghighi, Shan He, Gerardo Casañola Martín, Bakhtiyor Rasulev, Cristian R. Munteanu, Harbil Bediaga-Bañeres, Brenda Durán Ordiales, and Santiago Rodríguez Yáñez: Python scripting, machine learning model development, data analysis, manuscript writing, and figure preparation.Brenda Durán Ordiales, Raquel Esteban, Ana María Heres, Jorge Curiel Yuste, and Lur Epelde: Design and execution of the experimental methodology for the generation of the metagenomic data used in the SODDNA/SOHDNA model.Sonia Arrasate, Humberto González-Díaz, Tomás G. Villa, Alejandro Pazos, and Bakhtiyor Rasulev: Conceptualization of the study, supervision, manuscript writing, and funding acquisition.

# Funding
This project was funded by grants INCITE07PXI203141ES (Conselleria de Industria, Xunta de Galicia, Spain) and BFU2009-07745 (MINECO, Spain).  Likewise, the authors recognize the support of the National Science Foundation under the NSF MRI award OAC-2019077, and support by the State of North Dakota. CCAST HPC System supercomputing support at NDSU is acknowledged. In addition, the work was partly supported by Basque Government / Eusko Jaurlaritza (IT1558-22) and (IT1648-22), SPRI ELKARTEK grants AIMOFGIF (KK-2022/00032), Ministry of Science and Innovation (PID2022-137365NB-I00), and LANBIDE, INVESTIGO, Eusko Jaurlaritza, Grants, IKERDATA 2022/IKER/000040, funded by NextGenerationEU funds of European Commission,  likewise UDC Inditex Artificial Intelligence in Green Algorithms, funded by the Ministry for Digital Transformation and the Civil Service and 'NextGenerationEU'/PRTR under grant TSI-100925-2023-1 and Xunta de Galicia Consolidated group, grand ED431C 2022/46. JCY and RE are members of the Spanish climate-induced forest decline (ReDec) funded by MCIN/AEI (grant RED2024-153822-T).Moreover Fig. 1: General workflow and TOC were created with a licensed version of BioRender.com.
