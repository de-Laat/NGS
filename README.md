# NGS

For NGS, we have analysed short read illumina data & long read nanopore data to find out what species the data came from. For this, we followed the following workflow:


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
A statistical summary
A number of plots
A HTML summary file

## Unicycler
Used for genome assembly.

## Prokka
Used for genome annotation.

## Busco
Assess genome assembly and annotation completeness.

## Quast
Genome assembly quality.

## Kraken2
Assign taxonomic labels to sequencing reads.

## Roary

## starAMR
scans genome assemblies for AMR (AntiMicrobial Resistance) genes.
