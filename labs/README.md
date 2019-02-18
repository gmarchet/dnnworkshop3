# DNN Workshop Labs

## Overview

These folders contain a variety of notebooks and scripts intended as labs to support the DNN Workshop.  Content is based on material that was originally published on git ([LearningAnalytics](https://github.com/Azure/learnAnalytics-DeepLearning-Azure)).  

## Databricks Workspace / Databricks Cluster (CPU or GPU)

The delivery of this DNN workshop will use an Azure service called Databricks ([Databricks](https://databricks.com/)). Databricks is a clooud managed serice that provides a spark infrastructure for building machine learning and deep learnig data pipelines.  An interactive workspace is built around a managed spark cluster that can expose R, Scala, Python, and SQL intrfaces.  For this lab we will be using Python hossted in a Databricks Notebooks which has a similar look and familiar to Jupyter or Zeppelin notebooks.  For these labs it is recommended you run on a Databricks CPU cluster but you also have the option of running on a GPU-enabled Databricks cluster that are currently in Beta.    

## Pre-requisites

These labs have the following prerequisites that are detailed out in the Setup document. 

- An Azure subscription: To obtain one if you don't already have access, see ([Get Azure Free Trial](https://azure.microsoft.com/en-us/free/)).
- Sufficient cores to run a CPU or GPU enabled Databricks cluster.  Check to see if your subscripition has suffient ([quota for cores](https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits)). If you need to increase the quota, ([open a support Request from your azure portal](https://docs.microsoft.com/en-us/azure/azure-supportability/resource-manager-core-quotas-request))
- Create a Databricks workspace and Databricks cluster 
- Download the git repro to a folder on your local machine

