## **COURSE NAME AND CODE:** COMP ANALY HIGH-TP BIOMED DATA: 25499

### **Programmer:** Sharmila Tummala

Date: 03/06/2025

### **Programming Language:** 
Python

### **Python version:** 
Python 3.11.11

### **Description:** 
I am submitting a python script that allows to calculate the transcript half lives for the yeast genes using the 60 minute time series data provided in the file ‘DecayTimecourse.txt’
It handles the data in a methodical manner, calculating the half-lives of every transcript across three replicates.  An essential step in determining precise half-life numbers is exponential curve fitting, which is accomplished by the script using the curve_fit function from the scipy.optimize package.  It also detects genes with notably low (bottom 10%) and high (top 10%) half-lives, offering information on the dynamics of regulating gene expression.

### Files needed:
you need DecayTimecourse.txt

### Packages needed: 
This python code needs numpy, pandas  and scipy

### Output Files:
DecayTimecourse.csv: The converted csv file from the input txt file.

Half_Lives_Calculated.csv: Contains the computed half-lives for each yeast gene transcript.

high_half_life_genes.txt: Lists the identifiers of genes with high half-lives (top 10%).

low_half_life_genes.txt: Lists the identifiers of genes with low half-lives (bottom 10%).


### How to run my program
I am submitting a google colab file in this zip file you can run it by clicking on the link in the .ipynb file

if you are using VScode
1. make sure the python extension is installed
2. download .ipynb file and open it using VScode and run the program by clicking on the run button present on the top right corner

### NOTE
1. Python has various IDEs, running this python file completely depends on the IDE you are using.
2. Keep python file and matrix files in the same folder.
3. If you can't access the file please give full file path 

### Further Analysis:
After identifying genes with high and low half-lives, I perform a functional enrichment analysis using online tools such as g:Profiler to explore the biological significance of these genes in Saccharomyces cerevisiae S288C. Once the analysis is completed, the following PNG files are generated:

low half-life genes_detailed result.png: Provides a comprehensive visualization of genes with low half-lives (bottom 10%).

high half-life genes_detailed result.png: Offers a detailed visualization of genes with high half-lives (top 10%).

low half-life genes overview.png: Presents an overview visualization of genes with low half-lives (bottom 10%).

high half-life genes overview.png: Offers an overview visualization of genes with high half-lives (top 10%).


