create env

```bash
conda create -n wineq python=3.7 -y
```

activate env

```bash
conda activate wineq
```

created a req file

install the req

```bash
pip install -r requirements.txt
```

    You can get the data from here

https://drive.google.com/drive/folders/1jQ6GRth86GoYZAPa113h6LFnQoH5TgK-

```bash
git init
```

```bash
dvc init
```

```bash
dvc add data_given/winequality.csv
```

```bash
git add .
```

```bash
git commit -m "first commit"
```

```bash
git remote add origin git remote add origin https://github.com/Fortunatetech/Wine-quality-Prediction-MLOps-with-Deployment.git
git branch -M main
git push origin main
```

tox command -

```bash
tox
```

for rebuilding -

```bash
tox -r
```

pytest command

```bash
pytest -v
```

setup commands -

```bash
pip install -e .
```

build your own package commands-

```bash
python setup.py sdist bdist_wheel
```
