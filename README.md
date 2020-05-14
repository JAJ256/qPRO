# Supplemental Data and Code for 'A rapid, sensitive, scalable method for Precision Run-On sequencing (PRO-seq)'

Julius Judd<sup>1</sup>

<sup>1</sup>Department of Molecular Biology and Genetics, Cornell University, Ithaca, New York 14835, USA


This is a GitHub repository that contains supplemental data and analysis code for the paper "A rapid, sensitive, scalable method for Precision Run-On sequencing (PRO-seq)".  

## Data
The folder bw contains strand-specific bigWig tracks of raw signal for each replicate of each experiment. The subdirectory "merged_normed" contains reads-per-million (RPM) normalized replicate-merged signal for each experiment.  
The folder "dREGpeaks" contains bed files with dREG peaks called for each experiment. 


## Analysis code
All code used for analysis can be found in the file "supplemental.code.Rmd", or in the accompanying pdf file.  

## UCSC trackhub
The file "hub.txt" can be loaded at the UCSC genome browser here: [https://genome.ucsc.edu/cgi-bin/hgHubConnect]. Paste the raw url (https://raw.githubusercontent.com/JAJ256/qPRO/master/hub.txt) and click "Add Hub".

## Cost/Time comparison
The file "CostTimeComparison.pdf" compares the cost and hands-on time requirements for PRO-seq and qPRO-seq protocols. 




