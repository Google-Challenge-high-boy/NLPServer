# NLPServer

This repository is forked from Semantle-ko 

## Setup
``` 
cd data
wget https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.en.300.vec.gz
gzip -d cc.en.300.vec.gz
```
## requirement
```
uvicorn

```
### create word vector db

``` 
python process_vecs.py
python generate_secs.py
python -m uvicorn main:app --reload --host=0.0.0.0 --port=nnnn

```


