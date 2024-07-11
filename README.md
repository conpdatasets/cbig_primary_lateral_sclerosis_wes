# OVERVIEW

- Project name: Primary Lateral Sclerosis Whole Exome Sequencing
- Project location: The Montreal Neurological Institute and Hospital, Montreal, Quebec
- Last updated: November 2022
- Contact email address: neurobioinfo@mcgill.ca, https://neurobioinfo.github.io/

The Montreal Neurological Institute and Hospital (The Neuro) Bioinformatics Core is responsible for processing, consolidating, and storing the genomics data generated for the range of studies being performed by the institute’s researchers and clinicians. As such, the data are sorted into sets based on the sequencing methodology used and the phenotype of study. The Neuro's commitment to open science practices have resulted in all of the data being made publicly available through the C-BIG initiative, following appropriate ethical approvals and the principal investigator(s) consent.

Largely, these genomics datasets were generated for the purposes of novel gene-disease relationship discovery, although other analyses may have also been performed. We recommend contacting the recruiting principal investigator(s), outlined below, for full details regarding the previous use of these datasets.

### Dataset contents
- 46.5712 GB
- FASTQ files, BAM alignments, and gVCF/VCF files
- 11 Subjects

## METHODS

### -- Recruitment --
Patients diagnosed with Primary Lateral Sclerosis were recruited at The Montreal Neurological Institute and Hospital (The Neuro) in the clinic of Dr. Guy Rouleau. All indivduals provided informed consent.

### -- Data Acquisition --
Whole blood was obtained from all individuals and DNA was isolated. Whole exome sequencing was performed using either the Illumina NovaSeq 6000 or the Illumina HiSeq. Sequencing reads were processed using a Burrows-Wheeler Aligner (BWA) alignment, Genome Analysis Toolkit (GATK)/Picard post-alignment, and GATK HaplotypeCaller calling pipeline.

Sequencing details: 
 
                          Machine-pairing Sequencing_center Capture_type_kit       Date
                        ABI_SOLID4_Single              SteJ   Exome_SS_50Mbp 2011_03_10
                    Illumina_HiSeq_paired                IC      Exome_NG_V3       2015
                    Illumina_HiSeq_Paired                IC      Exome_SS_V4 2013_10_10
                    Illumina_HiSeq_Paired          Macrogen       Exome_SSV5 2019_08_29
                    Illumina_HiSeq_Paired          Macrogen      Exome_SS_V5 2021_10_18
