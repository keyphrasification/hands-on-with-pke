# Hands-on with `pke`

This repository contains the jupyter notebooks used for the hands-on session with the `pke` toolkit of the keyphrasification tutorial organised at ECIR 2022.

## Requirements

 * Python 3
 * Virtualenv
 * git

## Getting Started

```
# clone the tutorial code
git clone https://github.com/keyphrasification/hands-on-with-pke.git
cd hands-on-with-pke

# set up a virtual environment for Python
virtualenv -p python3.9 venv
source venv/bin/activate

# install jupyter notebook
pip install notebook

# install pke
pip install git+https://github.com/boudinfl/pke.git

# install additional/external resources:
python -m nltk.downloader stopwords
python -m nltk.downloader universal_tagset
python -m spacy download en_core_web_sm

# install matplotlib for graph visualization
pip install matplotlib
```
