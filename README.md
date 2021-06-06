# KubeflowPipelinesPractice

A simple repository for practicing Kubeflow Pipelines and Vertex AI Pipelines

## Step 1. Create a Docker image / pipelines component

Code is contained in the `component/` directory.

**Note:** Before following the KFP tutorial, you must have done the following:

* Installed the Google Cloud SDK.
* [Configure Docker to use the `gcloud` command](https://cloud.google.com/container-registry/docs/quickstart)
* [Enabled the Container Registry API on GCP.](https://cloud.google.com/container-registry/docs/quickstart)
* [Complete authentication for the Container Registry API on GCP.](https://cloud.google.com/container-registry/docs/advanced-authentication)
* [Learn how to push an image to a registry](https://cloud.google.com/container-registry/docs/pushing-and-pulling?&_ga=2.164634047.-187040626.1623008952#pushing_an_image_to_a_registry)

References:

+ [KFP tutorial](https://www.kubeflow.org/docs/components/pipelines/sdk/component-development/)
+ [Docker file reference](https://docs.docker.com/engine/reference/builder/)
+ [Docker file best practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
+ [Container Registry Quickstart](https://cloud.google.com/container-registry/docs/quickstart)

