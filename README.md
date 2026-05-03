[![Python 3.x](https://img.shields.io/badge/Python-3.X-green.svg)](https://www.python.org/)
[![HyLnc]((http://www.csb.iitkgp.ac.in/applications/HyLnc/index.php).
HyLnc uses customized BERT-based model combined with RandomForest algorithm to classify and predict sequences as lncRNAs or pcRNAs using combination of BERT-based embeddings and traditional handcrafted sequence features.

# Contents
- [Contents](#contents)
- [Requirements and installment](#requirements-and-installment)
- [Basic usage](#basic-usage)
- [Study demo](#study-demo)


# Requirements and installment
This software is developed with Python 3.X, Python 3.X is required as runtime environment.

```shell
git clone https://github.com/amrit-debug/HyLnc
cd HyLnc
gunzip HyLnc.zip
cd HyLnc
# virtual environment are recommended
python3 -m venv "/path/to/venv" (or conda environment)
pip install -r requirements.txt
```
# Basic usage
Users can use HyLnc to classify and predict lncRNA sequences.

```usage:
python3 HyLnc.py -i <input.fasta> -t <num of threads> -o <output.csv>
```
# Study demo
Users can submit only RNA sequences in FASTA format as input and must provide an output file name:

The input file must be present in "/path/to/HyLnc".

```shell
python3 HyLnc.py -i <input.fasta> -t <num of threads> -o <output.csv> 


2. The outfile containing the predictions will be present in 
"/path/to/HyLnc"
