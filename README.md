# BQML Model Export to AI Platform Prediction

This set of notebooks illustrates the concepts of training a model in BQML, extracting the model, and then loading the model to AI Platform Prediction for online serving, as well as orchestrating the workflow in Kubeflow Pipelines.

In order to run these notebooks, the following setup will need to be performed.  Ensure a GCP project is already created.

### Configure environment

From the console, open an instance of Cloud Shell.

Set project:
```
export PROJECT_ID=[]
gcloud config set project ${PROJECT_ID}
```
Enable services:
```
gcloud services enable \
bigquery.googleapis.com \
ml.googleapis.com \
notebooks.googleapis.com
```
### Create an AI Platform Notebook instance



### Create an AI Platform Pipelines instance

Follow the instruations for [Setting up KF Pipelines](https://cloud.google.com/ai-platform/pipelines/docs/getting-started#set_up_your_instance) to create an instance of AI Platform Kubeflow Pipelines.

After the KF Pipelines instance is created, from the console, click on `SETTINGS` and locate the `"host=..."` under "Connect to this Kubeflow Pipelines instance..."  Use this value for KFPHOST in the [Pipelines](02-bqml-to-caip-pipeline.ipynb) notebook.



