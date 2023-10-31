# lab10_yeast_human

This week we are going to find orthologs between genes in the human genome and your yeast genome. We will use blast to do search the human chromosome 1. 

## Step 1 - Folder setup

### Step 1a - Create lab 10 folder

From your home directory you will need to create a new folder for lab 10. 

### Step 1b - Copy the "clear" protein sequences

You will need to copy the "clear" version of your protein sequences. Reminder the "clear" version has removed all the duplicate sequences. 

The file name should be "clear_SRR00000.prot.fasta" and it is in several of the folders we have created this semester. 

### Step 1c - Copy human chromosome 1

There is a copy of all the proteins in human chromosome #1 in the class folder. 

The directory is ```/projects/class/binf3101_001/human_chr/chr1.fasta```. Copy this file into your new Lab 10 folder

**Your folder should now contain the following files**
- clear_SRR00000.prot.fasta
- chr1.fasta


## Step 2 - Create a blast Database

We have been using fasta files as both our query and our subject in previous blast searches. This time we will want to speed up the process by creating a **blast database**. This formats the data so it is easier to search. 

### Step 2a - load blast

w
