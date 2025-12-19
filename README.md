# Resources

I ran this code on my laptop with:
Chip: Apple M3 Max
Total Number of Cores: 14 (10 performance and 4 efficiency)
Memory: 36 GB

I did not run parallel jobs, I ran this locally using VSCode.

## Virtual Environment

Set your virtual environment to use the following version of Python:
    v3.13.3

If you do not have a virtual environment set up you can run the following commands on the terminal:
```bash
python3 -m venv venv   
```
  
```bash
source venv/bin/activate 
```


## Installation

Use the package manager pip to install the dependencies.

```bash
pip install requests pandas matplotlib scikit-learn seaborn gensim nltk spacy numpy
```

## spaCy

You should run the following command in the terminal after activating the virtual environment

```bash
python -m spacy download en_core_web_sm
```

## Executing the code

The datasets have been provided, and you should not re-run the dataset generation cells to ensure reproducible results.
To use the notebook you can simply select "Run all" to run all cells.


I have worked independently.