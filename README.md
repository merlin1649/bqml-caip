# BQML Model Export to AI Platform Prediction

This set of notebooks illustrates the concepts of training a model in BQML, extracting the model, and then loading the model to AI Platform Prediction for online serving, as well as orchestrating the workflow in Kubeflow Pipelines.

In order to run these notebooks, the following setup will need to be performed.  Ensure a GCP project is already created.

Authenticate to GCP and set project:
`gcloud auth login`
`export PROJECT_ID=[]`

[Setting up KF Pipeline](https://cloud.google.com/ai-platform/pipelines/docs/getting-started#set_up_your_instance)
