# Computational Practical X: Multilocus sequence typing (MLST) and cgMLST prediction from bacterial genomes



## Table of contents

1.	Introduction
2.	Expected learning outcomes
3.	Genomes for MLST and cgMLST analysis
4.	MLST prediction using mlst-check
5.	cgMLST prediction using chewBBACA
6.	MLST and cgMLST comparative visualisation (Phyloviz and GrapeTree)
7.	Q&A



## 1. Introduction

The ability to distinguish among strains of clinically relevant pathogens enables: (1) identification of circulating genotypes that may differ by features of virulence or antimicrobial resistance (AMR), (2) identification of outbreaks events, and (3) ability to track the source and spread of infections. Multilocus sequence typing (MLST) is a widely used molecular typing tool that is portable, universally adapted and provides a standardised genotypic approach that examines the nucleotide sequences of typically seven loci that encode house-keeping genes ([Maiden. 2006](https://www.annualreviews.org/content/journals/10.1146/annurev.micro.59.030804.121325)). Hundreds of MLST schemes for different pathogens have been made publicly available to ensure that a uniform nomenclature for typing is accessible through sites such as [PubMLST]( https://pubmlst.org/). 

Current advancements and cost-efficiency in generating high-throughput whole-genome sequencing data has led to the expansion of some MLST schemes to core-genome MLST (cgMLST) schemes that include >1000 genes to create sequence types that provide increased resolution for clonal populations of bacteria ([de Been et al. 2015](https://journals.asm.org/doi/full/10.1128/jcm.01946-15)). Following the increase in the number of whole-genomes, PubMLST is increasingly including whole-genome sequences accessed through BIGSdb ([Jolley and Maiden. 2010](https://link.springer.com/article/10.1186/1471-2105-11-595)).

Several bioinformatics tools that identify MLST sequence types directly from the genome have been developed. For example, [mlst-check](https://github.com/sanger-pathogens/mlst_check) enables the identification of sequence types by first consolidating multiple MLST databases from various sources into one database that can be stored locally and kept up-to-date. FASTA files can then be used as input to get sequence types from a corresponding pathogen specific database as well as the genomic sequences for each allele. Similarly, tools for cgMLST have been implemented. An example is [chewBBACA](https://github.com/B-UMMI/chewBBACA) a software used to create and evaluate cgMLST or whole-genome MLST (wgMLST) schema. chewBBACA creates schemas and allele calls on whole genomes resulting from de novo assemblers. For this practical session, [GrapeTree](https://github.com/achtman-lab/GrapeTree) will be used for visualisation.  



## 2. Expected learning outcomes

At the end of this practical session, one should be able to:  
  \-	Use command-line tools such as mlst-check and chewBBACA to identify isolates’ MLST and cgMLST profiles or sequence types;  
  \-	Use tools such as PHYLOViZ and GrapeTree to visualise MLST and cgMLST results, respectively;  
  \-	Compare and contrast the two methods and when each is useful  



## 3. Genomes for MLST and cgMLST analysis

### Data preparation

Navigate to your home directory and create a new mlst directory.

```
cd
mkdir mlst
```

Inside the mlst directory, create another directory called genomes

```
cd mlst
mkdir data
```

Copy genomes (.fa) from xx into data directory 

```
cp ...

```

## 4. MLST prediction using mlst-check

mlst-check is currently pre-installed for this course. 






## 5. cgMLST prediction using chewBBACA




## 6. MLST and cgMLST comparative visualisation (Phyloviz and GrapeTree)




## 7. Q&A














