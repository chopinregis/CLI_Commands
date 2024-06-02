https://cloud.google.com/sdk/docs/cheatsheet

https://cloud.google.com/static/sdk/docs/images/gcloud-cheat-sheet.pdf

# Google Cloud SDK Cheat Sheet

## Getting Started
- `gcloud init`: Initialize, authorize, and configure the gcloud CLI.
- `gcloud version`: Display version and installed components.
- `gcloud components install`: Install specific components.
- `gcloud components update`: Update your gcloud CLI to the latest version.
- `gcloud config set project`: Set a default Google Cloud project to work on.
- `gcloud info`: Display current gcloud CLI environment details.

## Help
- `gcloud help`: Search the gcloud CLI reference documents for specific terms.
- `gcloud feedback`: Provide feedback to the gcloud CLI team.
- `gcloud topic`: Supplementary help material for non-command topics like accessibility, filtering, and formatting.

## Personalization
- `gcloud config set`: Define a property (like compute/zone) for the current configuration.
- `gcloud config get`: Fetch the value of a gcloud CLI property.
- `gcloud config list`: Display all the properties for the current configuration.
- `gcloud config configurations create`: Create a new named configuration.
- `gcloud config configurations list`: Display a list of all available configurations.
- `gcloud config configurations activate`: Switch to an existing named configuration.

## Authorization and Credentials
- `gcloud auth login`: Authorize Google Cloud access for the gcloud CLI with user credentials.
- `gcloud auth activate-service-account`: Authorize Google Cloud access with service account credentials.
- `gcloud auth application-default`: Manage Application Default Credentials (ADC).
- `gcloud auth list`: List all credentialed accounts.
- `gcloud auth print-access-token`: Display the current account's access token.
- `gcloud auth revoke`: Remove access credentials for an account.

## Projects
- `gcloud projects describe`: Display metadata for a project.
- `gcloud projects add-iam-policy-binding`: Add an IAM policy binding to a specified project.

## IAM
- `gcloud iam list-grantable-roles`: List IAM grantable roles for a resource.
- `gcloud iam roles create`: Create a custom role for a project or organization.

## Docker & Google Kubernetes Engine (GKE)
- `gcloud container clusters create`: Create a Kubernetes cluster.
- `gcloud container clusters get-credentials`: Get credentials for a cluster.
- `gcloud container clusters list`: List all clusters.
- `gcloud container clusters delete`: Delete a cluster.

## Virtual Machines & Compute Engine
- `gcloud compute instances create`: Create a new Compute Engine instance.
- `gcloud compute instances list`: List all Compute Engine instances.
- `gcloud compute instances delete`: Delete a Compute Engine instance.

## Serverless & App Engine
- `gcloud app deploy`: Deploy an application to App Engine.
- `gcloud app describe`: Display information about your App Engine application.
- `gcloud app browse`: Open the current application in a web browser.

## Miscellaneous
- `gcloud config set disable_prompts`: Disable interactive prompts.
- `gcloud services list`: List all the services available for the current project.
- `gcloud services enable`: Enable a service for the current project.
