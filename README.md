## create env
```bash
conda create -n wineq python=3.7 -y
```
## activate env
```bash
conda activate wineq
```
## created requirements.txt

### install the requirements.txt
```bash
pip install -r requirements.txt
```
## download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

git init

dvc init

dvc add data_given/winequality.csv

git add . 

git commit -m "first commit"

## tox command -
```bash
tox
```

## for reebuilding -
```bash
tox -r
```
## pytest command -
```bash
pytest -v
```

## setup commands -
```bash
pip install -e .
```

## build your packages command -
```bash
python setup.py sdist bdist_wheel
```

## mlflow server command -
mlflow server \
--backend-store-uri sqlite:///mlflow.db \
--default-artifact-root ./artifacts \
--host 127.0.0.1 -p 1234


