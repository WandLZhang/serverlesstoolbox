# Deploying an API for Coud SQL using Cloud Run

## Overview
This tutorial has example scripts to deploy a Cloud SQL database and an API to Cloud Run, forked from [momander/serverlesstoolbox](https://github.com/momander/serverlesstoolbox/tree/master/rest-api-sql).

The database houses appointments made to a social services government agency, and the API enables GET, POST, and DELETE to the database.

## How to deploy
Run the following scripts from your terminal (e.g., "source ./create-database.sh"):
 - create-database.sh
 - deploy-rest-api.sh
 
 making sure to replace the variable names with the GCP configuration you desire.