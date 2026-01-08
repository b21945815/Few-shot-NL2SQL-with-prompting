# Few-shot-NL2SQL-with-prompting

## Table of contents
* [Dataset](#dataset)
* [Setup](#setup)
* [Citation](#citation)


## dataset
INSTALL THE DATA FROM https://bird-bench.github.io
IN YOUR PROJECT UNZIP THE DATA TO A FOLDER NAMED DATA
DATA
 --dev_20240627
 --train

make .env file
set OPENAI_API_KEY=key


## setup
To run this project, use the following commands:

```
$ pip3 install -r requirements.txt
$ echo "Start running DIN-SQL.py"
$ python3 DIN-SQL_BIRD.py 
$ echo "Finished running DIN-SQL.py"
```
## citation 

``` 
@article{pourreza2023din,
  title={DIN-SQL: Decomposed In-Context Learning of Text-to-SQL with Self-Correction},
  author={Pourreza, Mohammadreza and Rafiei, Davood},
  journal={arXiv preprint arXiv:2304.11015},
  year={2023}
}
```

