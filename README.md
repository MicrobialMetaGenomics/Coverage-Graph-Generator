# Coverage Graph Generator 
<div><img src="https://github.com/mohammedemamkhattab/CGGS/assets/134694182/f786dfb1-dbf0-4873-a64c-63ee2a352d94" width="250"/> </div>
Script for the Microbial Metagenomics laboratory, University of Padova A.Y. 2023/2024. Students-project


### NOTICE
#### This code was developed as part of a project carried out during the course of Microbial Metagenomics (Molecular Biology master degree) at the University of Padova. The project was supervised by Prof. Stefano Campanaro, and Dr. Esteban Orellana. The project was made by Elena Cibola, Maria Agustina Biancalani, Mohamed Khaled, and Mohammed Emam.

## Introduction 
#### The objective of the project is to estimate the percentage of the coverage of reads for different samples provided as Metagenome-Assembeled Genomes (MAGs), which is a fundamental task in metagenomic analysis. Supplied with Graph generation CGG creates a visual representations that illustrate the extent to which genomic regions have been covered or traversed. In genomic analysis, coverage graphs play a crucial role in understanding the sequencing depth and coverage across the genome. By visualizing the distribution of sequencing reads or alignments across genomic regions, researchers can evaluate the quality of the data, detect potential gaps or biases, and make informed decisions about downstream analysis such as identifying different influences acting on different samples provided. Moreover, coverage graphs in genomics aid in variant detection, genome assembly validation, and identification of structural variations.

### **Breadth of coverage**
   #### the fraction of the genome that is covered by the reads obtained from the sequencing. Reads are aligned on the reference to calculate this.
   
## Using CGG 
### Requirements 
#### The software requires at least 8 GB of RAM.

### Input
#### For the MAGs files generated the sofware uses the fna (fasta nucleic acid) format, this format is slightly different from FASTA as each different sequence in the file are distincted from the other with a title, but both formats uses the FASTA. Using the next line you can change the format of your file but remember that the content and format of the file remain unchanged during the conversion. (make sure to install the required packages if not present).
```{python}
mv input.fasta output.fna
```

### Output
#### From the first step: the depth file contains multiple columns (Contigs, Position, Sample 1 reads, Sample 2 reads, Sample 3 reads, Sample 4 reads). Secondly, Creation of the pycircos image file that resembles the distribution of the reads across the sequences of the samples represented in circles. Lastly, the table generated that contains the coverage percentages as a _CSV_ file that contains multiple columns (MAGs, Associated Contigs, Sample 1 coverage, Sample 2 coverage, Sample 3 coverage, Sample 4 coverage).

### Limitations
### mmmmmmmmmmmmmmmmmmmmm
