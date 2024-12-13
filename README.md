 # Script for scientific article "Genetic evolution of DENV2 in the French territories of the Americas: A retrospective study from the 2000s to the 2024 epidemic, including a comparison of amino acid changes with vaccine strains"
 
## Description
This program allows identifying the protein substitutions of a set of strains in comparison to a reference strain, and highlighting them in an Excel file.
We used this Python script to compare DENV vaccine strains (Qdenga and Dengvaxia) and a sequence alignment of DENV2. 

## Prerequisites
- Python or Replit
- Import:
import pandas as pd
import numpy as np
from Bio import SeqIO
from pandas.core.frame import dataclasses_to_dicts
#Install BioPython in the shell: pip install biopython
#Install pandas in the shell: pip install pandas openpyxl
#Install Jinja2 in the shell: pip install jinja2
- Libraries required: BioPython
- The data containing the strains must be in a .fa (FASTA) file.

## Usage
1. Download this script.
2. Run it with input files:
   Dengvaxia_alignement_input
   Qdenga_alignement_input

## Quote
If you use this script, please quote our article. 
