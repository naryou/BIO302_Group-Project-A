# BIO302_Group-Project-A

*Students: Melisa & Michelle*

## General questions for your project
*What does it take from sequencing to a reference genome?* 
- address different sequencing techniques, the value and weekpoints of them 
- different assemblers (why so many of them??)
- discuss the quality of a reference genome assembly (what are the gold standards and what is 'acceptable' to address genomics-related questions)

*While focusing on these type of questions, review the avaialbe methods/software, explain how they work and results that you get from them* 

## Study system
*Primula boveana* (Primulaceae)

Endemic to Sinai, Egypt; critically endangered with only ca. 200 individuals in the wild. Homostylous (only one flower morph, due to loss of heterostyly)

- Genome size: 450Mb (Flow Cytometry and K-mer count)
- Ploidy: diploid, 2n=20
- Data generated: Nanopore (100x total), WGS shotgun, Hi-C (Arima) 

![Primula boveana][Pboveana_UZH_greenhouse_NY]

[Pboveana_UZH_greenhouse_NY]: ./Pboveana_UZH_greenhouse_NY.jpg


## On this [Galaxy history](https://usegalaxy.eu/u/naryou/h/bio302genome-assembly-a), you find the following data

- Whole  Genome Shotgun Sequencing of Primula boveana. This is Illumina short reads, paired-end (PE), 150bp. The files 20220128.A-Pboveana_I1.fastq.gz and 20220128.A-Pboveana_I2.fastq.gz (which have **I**), are small versions of the larger WGS data set. *Narcis will give you the larger datasets alao*
- Nanopore reads of Primula boveana.
- Hi-C data. This is also Illumina short reads, paired-end (PE), 150bp, but the read1 and read2 come from stretches of DNA which are in close distance in 3D. 
To refresh your knowledge on Hi-C data, have a look at LEC2, NGS data generation and handling.

& Narcis will give you fasta and graph files of ref. genome assembly of the same nanopore data with Flye for comparison.

## The project will be done in four steps:
- genome profiling using GenomeScope2
- assembly using ABySS (for short reads) and Shasta (for long reads)
- scaffolding using YaHS
- annotation using Repeat Modeler (and Maker if we have time)

You find tutorials for genome profiling, assembly, scaffolding and annotation in this repository. Just navigate to different directories.


