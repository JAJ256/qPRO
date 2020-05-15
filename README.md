# Supplemental Data and Code for 'A rapid, sensitive, scalable method for Precision Run-On sequencing (PRO-seq)'

Julius Judd<sup>1</sup>\*, Luke A. Wojenski<sup>2</sup>\*, Lauren M. Wainman<sup>2</sup>\*, Nathaniel D. Tippens<sup>1</sup>, Edward J. Rice<sup>3</sup>, Alexis Dziubek<sup>1,2</sup>, Geno J. Villafano<sup>2</sup>, Erin M. Wissink<sup>1</sup>, Philip Versluis<sup>1</sup>, Lina Bagepalli<sup>1</sup>, Sagar R. Shah<sup>1</sup>, Dig B. Mahat<sup>1</sup>, Jacob M. Tome<sup>1</sup>, Charles G. Danko<sup>3,4</sup>, John T. Lis<sup>1</sup>, Leighton J. Core<sup>2</sup>

\*Equal Contribution  
<sup>1</sup>Department of Molecular Biology and Genetics, Cornell University, Ithaca, New York 14835, USA  
<sup>2</sup>Department of Molecular and Cell Biology, Institute of Systems Genomics, University of Connecticut, Storrs, CT 06269, USA  
<sup>3</sup>Baker Institute for Animal Health, College of Veterinary Medicine, Cornell University, Ithaca, NY 14853, USA  
<sup>4</sup>Department of Biomedical Sciences, College of Veterinary Medicine, Cornell University, Ithaca, NY 14853, USA  
  
  
This is a GitHub repository that contains supplemental data and analysis code for the paper "A rapid, sensitive, scalable method for Precision Run-On sequencing (PRO-seq)".  

## Data
The folder bw contains strand-specific bigWig tracks of raw signal for each replicate of each experiment. The subdirectory "merged_normed" contains reads-per-million (RPM) normalized replicate-merged signal for each experiment.  
The folder "dREGpeaks" contains bed files with dREG peaks called for each experiment. 


## Analysis code
All code used for analysis can be found in the file "supplemental.code.Rmd", or in the accompanying pdf file.  

## UCSC trackhub
The file "hub.txt" can be loaded at the UCSC genome browser here: https://genome.ucsc.edu/cgi-bin/hgHubConnect. Paste the raw url (https://raw.githubusercontent.com/JAJ256/qPRO/master/hub.txt) and click "Add Hub".

## Cost/Time comparison
The file "CostTimeComparison.pdf" compares the cost and hands-on time requirements for PRO-seq and qPRO-seq protocols. 




