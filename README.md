# NGS

For NGS, we have analysed short read illumina data & long read nanopore data to find out what species the data came from. For this, we followed the following workflow:
This project was performed by: Sven Klomp, Manon Cortooms, Dirk de Laat, Jomi Leerssen and Lars Moret.

## Cutadapt 
Used to trim long read data.

## Trimmomatic
Used to trim short read data.

## FastQC
Used for quality report of reads and trimmed reads.

## MultiQC
Used to create a single report from the analysis.

## Nanoplot
Used to create:
A statistical summary,
A number of plots,
A HTML summary file.

## Unicycler
Used for genome assembly.

## Prokka
Used for genome annotation.

## Busco
Used to assess genome assembly and annotation completeness.

## Quast
Used for genome assembly quality.

## Kraken2
Used to assign taxonomic labels to sequencing reads.

## Roary
Used to find the sum of the core and accessory genomes (pan genome). 

## StarAMR
Used to scan genome assemblies for AMR (AntiMicrobial Resistance) genes.

##RAxML
Used to make the Phylogenomic tree.

## Phandago
Used to visualise roary.
