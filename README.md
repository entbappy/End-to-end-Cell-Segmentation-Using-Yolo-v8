# End-to-end-Cell-Segmentation-Using-Yolo-v8

## Workflows

1. constants
2. entity
3. components
4. pipelines
5. app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/entbappy/End-to-end-Cell-Segmentation-Using-Yolo-v8
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cell python=3.8 -y
```

```bash
conda activate cell
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


# AZURE-CICD-Deployment-with-Github-Actions

## Save pass:

S6tXzK7IxUHz9O/9jkhciLsseddeQ++E+OcD7nQYy8+ACRDtEgUW


## Run from terminal:

docker build -t cellseg.azurecr.io/cell:latest .

docker login cellseg.azurecr.io

docker push cellseg.azurecr.io/cell:latest


## Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 
