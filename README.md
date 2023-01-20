# Dagster Cloud Serverless Deployment Quickstart

Welcome to your Dagster Cloud sample code repo. Here, you can find the code that's being deployed to your Dagster Cloud instance. For more in-depth information, check out our [Serverless](https://docs.dagster.io/dagster-cloud/deployment/serverless) docs.

Pushing to production will automatically kick off a [workflow](./.github/workflows/deploy.yml) which will redeploy your code to your `prod` deployment.

Creating a pull request will kick off a [workflow](./.github/workflows/deploy.yml) which will create a new [**Branch Deployment**](https://docs.dagster.io/dagster-cloud/developing-testing/branch-deployments), an ephemeral deployment where you can test your changes.

