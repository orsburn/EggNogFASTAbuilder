# EggNogFASTAbuilder
Python script by ChatGPT4 which allows EggNoG protein annotations to be made the accession in protein FASTA files

EggNog Mapper is an amazing tool for rapidly assigning putative protein functions. However, you get out an Excel sheet with your old annotation and your new annotation.
That isn't super helpful to me for downstream proteomics.
This script takes your original FASTA and a two column Tab delimited text file that has your old accession and your EggNog generated accession.
The output is a new FASTA file with your new accessions. BOOOOOM. THAT is useful to me.

To execute this, put your query.fasta in a folder.
Take your EggNoG output and cut the Excel columns for your query and your new accession into two separate tab delimited columns. 
Put that in your folder.
Put this python script in the folder.
Run this python script.
It's magic. 
