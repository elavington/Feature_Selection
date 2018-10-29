# Feature_Selection
This folder contains Data and results used in the upcoming article "Machine learning based feature selection for classifying Circular Rep-encoding ssDNA viruses to genus" by Erik Lavington, Lele Zhao, and Siobain Duffy. 

Data.csv- Data used in training/testing supervised machine learning classifiers

Contml_nuccore_paired_samples.csv - CP and Rep protein sequences paired to generate data for input in Phylip contml
                                    Trivially, all CP and Rep sequences were paired by NCBI nuccore source id, matching these sequences
                                    to the same genomic segment
                                    Non-trivially, CP and Rep are found on separate genomic segments in Nanoviridae, and so were randomly
                                    associated by Species

CNN_feature_anova_data-data used to run ANOVA analysis of effects on CNN feature BLASTp subject-query Genus matching precision.

CNN CP Features/CNN Rep Features - These folders contain, for Rep and CP protein sequences:
                                      RESULTS (.result) downloaded from CD-HIT sequence clustering (http://weizhongli-lab.org/cd-hit/)
                                      FASTA files (.fasta)  of CD-Hit cluster representatives aligned to reference sequence
                                      BLASTp Hit Table (.csv) of eachcluster representative feature against the full NCBI non-redundant                                               protein sequence database
                                      
Trees- This folder contains:
                                      DATA (.txt) used as input in Phylip contml, continuous character Maximum Likelihood tree building                                               program 
                                      ANNOTATIONS (annot.txt) of data used in Figtree tree visualization program
                                      CONTML OUTPUT TREES (outtree...) raw output from Phylip contml
                                      SAVED TREES (...figtree) after annotation in Figtree
                                      
