## **COURSE NAME AND CODE:** COMP ANALY HIGH-TP BIOMED DATA: 25499

### **Programmer:** Sharmila Tummala

Date: 04/01/2025

### **Programming Language:** 
Python

### **Python version:** 
Python 3.11.11

### **Description:** 
I am submitting a Python script that performs motif detection using a Position Weight Matrix (PWM) to identify transcription factor binding sites in upstream regulatory regions of E. coli genes.

The script does the following:

Parses a custom-formatted counts matrix for the argR transcription factor.

Computes the adjusted frequency matrix F'(b, j) using pseudocounts.

Calculates the PWM (log-odds matrix) using a background frequency of 0.25.

Loads upstream sequences from a .bz2 compressed FASTA-like file.

Scans all sequences using the PWM and reports the top 30 binding sites with the highest PWM scores.

The sequences represent 400 bp upstream and 50 bp downstream regions for E. coli genes.

### Packages needed: 
This python code needs numpy and bz2
### How to run my program
I am submitting a google colab file in this zip file you can run it by clicking on the link in the .ipynb file
Upload both required input files:

argR-counts-matrix.txt

E_coli_K12_MG1655.400_50.bz2

if you are using VScode
1. make sure the python extension is installed
2. download .ipynb file and open it using VScode and run the program by clicking on the run button present on the top right corner

### NOTE
1. Python has various IDEs, running this python file completely depends on the IDE you are using.
2. Keep python file and input files in the same folder.
3. If you can't access the file please give full file path 
