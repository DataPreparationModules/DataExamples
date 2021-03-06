# DataExamples
This repository contains material used for discovering data preparation modules using data examples.

* The folder DataExamples/Experiment-SyntheticDataExamples/Eclipse Project/ contains the java source code that we used for generating the synthetic data sets for generating data examples, as well as the code for simulating feedback generation. 
* The folder DataExamples/Experiment-SyntheticDataExamples/Results/ contains the data that we obtained by running our experiment using the synthetic data, as well as the qinterpretation results, charts and SQL queries that helped us analyze the results.
* The folder DataExamples/Experiment-RealDataExamples contains a zip folder with the data examples that characterizes real world data preparation modules t that we used for our experiment. Information about the real-world modules that we descibed and the discovery queries that we used for experimentation are presented in what follows.

# Real-World Data preparation modules described using examples 

This repository contains data examples describing data preparation modules, which can be found in the folder data example.
A data example specify the name of the module, its provider, URI as well as the input and output. 
The inputs and outputs are described by a name and a semantic domain, as well as a value.

Here is the list of modules that we described using data examples:

* GenEntry (by DDBJ)
* FastaHeaderExtractor (by FABOX)
* FastaDatasetSplitter (by FABOX)
* Fasta2Excel (by FABOX)
* DNAcollapser (by FABOX)
* FastaToTCS (by FABOX)
* ARSA (by DDBJ)
* XQuest (by ETHZ)
* FindingExperiments (by EBI)
* SearchCHEBI (by the EBI)
* AssemblycDNA (by the EBI)
* AssemblyCDS (by the EBI)
* AssemblyMap (by the EBI)
* search_pathway (by Kegg)
* search_brite (by Kegg)
* search_disease (by Kegg)
* reconstruct_pathway (by Kegg)
* annotate_sequence (by Kegg)
* map_taxonomy (by kegg)
* GhostKOALA  (by Kegg)
* KofamKOALA (by Kegg)
* PREDIction of SIgnal peptides (by Predisi)
* Retrieve/ID (by Uniprot)
* PeptideSearch (by Uniprot)
* CutSeq (by Emboss)
* degapseq (by Emboss)
* entret (Emboss)
* trimset (by Emboss)
* union (by Emboss)
* vectorstrip (by Emboss)
* proteomecentral (by proteomecentral)
* GOlr (by Gene Ontology)
* GENEASE (by CCHMC)
* snp (by NCBI)
* Protein2GO (by QuickGO)
* GeneProducts (by QuickGO)
* DBFetch (by EBI)
* TestProbe (by ARB-SILVA)
* TestPrime (by ARB-SILVA)
* Phylogeny (by EBI)
* InterproScan (by EBI)
* PisaQuery (by EBI)
* microscopy density maps (by EBI)
* ePlant (by bar.utoronto)
* SGRP Blast (by csb.utoronto)
* SGBR extractSeqFragment (by csb.utoronto)
* FindGeo (by metalweb)
* Metal_S3 (by metalweb)
* MetalPredator (by metalweb)
* activity (by unipr.it)
* bib (by unipr.it)
* family (by unipr.it)
* pGenN (by udel)
* evex (by evexDB)
* chat (by lionproject)
* cancer-search (by pubmeth)
* brenda (by enzymes.org)


# Queries
We issues the following queries:
* Q1: What is the DNA sequence in an EBI format for a given DNA accession
* Q2: What are the pathways associated with a given gene term
* Q3: Format a Fasta biological sequence into a Uniprot format
* Q4: What is the GO term associated with a Protein Sequence
* Q5: What are the annotations associated with a biological sequence 

# Performance of our algorithm for discovering data preparation modules
| query  | keyword search |Input and output based search |Amount of feedback on data examples |
| ------------- | ------------- |------------- |------------- |
| Q1  | 30 candidate modules  | 6  | 2  |
| Q2  | 8 candidate modules  | 3  | 1  |
| Q3  | 31 candidate modules  | 8  | 4  |
| Q4  | 27 candidate modules  | 4  | 2  |
| Q5  | 31 candidate modules  | 1  | 1  |



