# keras-bert-ner

Named entity recognition built on top of BERT and keras-bert. 

## Dependencies:

bert (added as submodule to this project. FullTokenizer is used instead of keras-bert tokenizer)

keras-bert (https://pypi.org/project/keras-bert/)

Pretrained BERT model, e.g. from:
- https://github.com/TurkuNLP/FinBERT
- https://github.com/google-research/bert

input data e.g. from:
- https://github.com/mpsilfve/finer-data

Input data is expected to be in CONLL:ish format where Token and Tag are tab separated. 
First string on the line corresponds to Token and second string to Tag
  
## Quickstart

```
git submodule init
git submodule update
./scripts/get-models.sh
./scripts/get-finer.sh
```

