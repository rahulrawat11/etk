# etk
![travis ci](https://travis-ci.org/usc-isi-i2/etk.svg?branch=master)
This repository will contain our toolkit for extracting information from web pages.
It will be built in stages to contain the following capabilities:

* Several structure extractors to identify the main content of a page and tables
* A host of data extractors for common entities, including people, places, phone, email, dates, etc.
* A trainable algorithm to rank extractions
* Automated experimentation to measure precision and recall of extractions  
## Setup
`conda-env create .`  
`source activate etk_env`   
`python -m spacy download en`  

## Run Tests  
`python -m unittest discover`

## Launch Jupyter Notebook  
`jupyter notebook etk_examples.ipynb`  
or  
`jupyter notebook etk_extraction_using_config.ipynb`  

> Before running the code in the notebook, change the kernel to `Python [conda env:etk_env]`
