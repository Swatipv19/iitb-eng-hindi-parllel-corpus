# IITB-English-Hindi Parallel Corpus

## About 

We provide a notebook that shows how to import the IITB English-Hindi Parallel Corpus from the HuggingFace datasets repository. The notebook also shows how to segment the corpus using BPE tokenization which can be used to train an English-Hindi MT System.

The complete details of this corpus are available at [this URL]((https://www.cfilt.iitb.ac.in/iitb_parallel/)). We also provide this parallel corpus via browser download from the same URL.

## Usage

You should have the 'datasets' packages installed to be able to use the :rocket: HuggingFace datasets repository. Please use the following command and install via pip:

```code
     pip install datasets
```

In the notebook, we also provide the code to create Byte-pair encoding segmented version of this corpus. You can choose to tokenize it the way shown in the notebook, or use any other tokenization which also supports the Hindi language.
