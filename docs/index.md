# AI Software Template Gitops

This repository contains the necessary content required for managing Gitops. It was created as part of an AI Software Template. The associated source component is available for reference through the **Overview** tab. You can find an example of this below.

![Overview Tab](./images/overview-dependency.png)

# Deployed Resources
Based on the input from the AI Software Template, a deployment with the following characterisics was made:

# Model Server
**Model Server:** [detr-resnet-101]( https://github.com/containers/ai-lab-recipes/tree/main/model_servers/object_detection_python)

**Port:** 8000

# Application
An application built from https://github.com/jdubrick-ai/apr7-objectdetection-1 will be stored in [quay.io/jdubrick-ai/apr7-objectdetection-1](https://quay.io/jdubrick-ai/apr7-objectdetection-1) and deployed via Gitops. This application is accessible on port **8501**.