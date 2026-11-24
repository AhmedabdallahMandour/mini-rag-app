# mini-rag 

this is a minimal 


## requirements 

- python 3.8 or later 

### Install python using Miniconda 

1) Download and install Mininconda from [here]()

2) Create a new env using the following command: 

```bash 
$ conda create -n mini-rag python=3.8
```

3) Activate env:

```bash
$ conda activate mini-rag 
```


## Installation

### Install required backages

```bash
$ pip install -r src/requirements.txt
```

### setup the environment variables



## Run fastAPI server 

Run this command from the project root (`mini-rag-app`):

```bash
$ uvicorn src.main:app --reload --host 0.0.0.0 --port 8000
```

