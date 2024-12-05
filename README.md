# Chest-Disease-Classification-from-Chest-CT-Scan-Image


## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 



## Live matarials docs

[link](https://drive.google.com/drive/folders/1Zmu_r35QFpxAcBPAB4LphFX1cN1wXYVL?usp=drive_link)
[link](https://drive.google.com/)

## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.10.15 -y
```

```bash
conda activate chest
  or
source activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

## Mlflow dagshub connection uri
MLFLOW_TRACKING_URI = https://dagshub.com/Sarala9206/mlflowdemo.mlflow

MLFLOW_TRACKING_USERNAME = 

MLFLOW_TRACKING_PASSWORD = 

python script.py

## RUN from bash terminal

export MLFLOW_TRACKING_URI=

export MLFLOW_TRACKING_USERNAME=sarala9206 

export MLFLOW_TRACKING_PASSWORD=


import dagshub
dagshub.init(repo_owner='Sarala9206', repo_name='mlflowdemo', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

