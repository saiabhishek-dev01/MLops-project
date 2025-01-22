# MLops-project


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlops python=3.8 -y
```

```bash
conda activate mlops
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui



### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/saiabhishek-dev01/MLops-project.mlflow \
MLFLOW_TRACKING_USERNAME=saiabhishek-dev01 \
MLFLOW_TRACKING_PASSWORD=d0a83102f0e97fd3bb51aa187754dc40e1467e9b \

python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/saiabhishek-dev01/MLops-project.mlflow
export MLFLOW_TRACKING_USERNAME=saiabhishek-dev01
export MLFLOW_TRACKING_PASSWORD=d0a83102f0e97fd3bb51aa187754dc40e1467e9b

```




