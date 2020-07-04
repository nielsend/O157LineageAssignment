# O157 Lineage Assignment
A script that returns the LSPA6 lineage result for O157 *Escherichia coli* when given genomic data in a FASTA format.

The LSPA6 lineage typing is based on: 

[Yang Z, Kovar J, Kim J, Nietfeldt J, Smith DR, Moxley RA, Olson ME, Fey PD, Benson AK. 2004. Identification of common subpopulations of non-sorbitol-fermenting, beta-glucuronidase-negative *Escherichia coli* O157:H7 from bovine production environments and human clinical samples. Appl Environ Microbiol 70:6846-54.](https://aem.asm.org/content/70/11/6846/article-info)

<br>

### Assumptions
* If you are a USDA user with access, this program runs natively on CERES as of 7/1/2020.
* Python is installed on machine.
* User has bash terminal.

### Input
* Open Terminal
* Call program 
```./LSPA6Long.sh [output CSV File Name] [Fasta File(s)]```

### Output
* A .csv file will be created containing concise information about each strain or contig (as separated by >).
* Unless directed to a different location, the output CSV file will be created wherever the script is located.

E.g.: Output
Verbose output on the screen is also an output. This output can be sent to a file. 
```./LSPA6Long.sh [output CSV File Name] [Fasta File(s)] > Information.txt```
