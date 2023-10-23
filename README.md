##  Building Large Language Models (LLMs) Applications Workshop

This repository contains a collection of labs that equips you with the foundation to build and utilize generative AI applications on AWS. If you are at event with this workshop, you can begin by following the steps provided in the associated workshop link. 

<b>Associated workshop: https://catalog.us-east-1.prod.workshops.aws/workshops/5779400a-9bff-41c5-9f2c-2dcc8b71a374</b>

Pre-requisites for running this in your own environment:
Before you begin, we recommend that you [create and onboard to a SageMaker Studio Domain](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-studio-onboard.html). This requires an AWS Account, and a user with access to create the Domain. You can refer to the pre-requisites [here](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-set-up.html). Once that has been completed, [launch SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-launch.html) and open a "System Terminal" from the launcher, from which you can clone this repository: `git clone https://github.com/aws-samples/building-llm-applications.git`.

Lab 1: Text Generation
This lab introduces us to prompt engineering and building a chat assistant using LLMs. To start with, we will need to [deploy an endpoint through Amazon SageMaker JumpStart](https://docs.aws.amazon.com/sagemaker/latest/dg/jumpstart-deploy.html). We have tested the lab with [Falcon-7b-instruct](https://huggingface.co/tiiuae/falcon-7b-instruct) as the LLM. We will go through the basics of using commonly used techniques and tools with LLMs, e.g. Langchain, using retrieval augmented generation (RAG) to bring our own knowledge base into the prompt for the large language model (LLM), and using LLM to understand intent and extract information to be stored into an RDBMS database. 

Lab2: Image Generation
This lab walks us through fine tuning a [Stable Diffusion model](https://huggingface.co/stabilityai/stable-diffusion-2-1-base) to bring a custom logo into images e.g. MyCompanyLogo on painting on a wall. We will leverage Amazon SageMaker for the development environment (with SageMaker Studio), training job (with SageMaker Training Job), hyperparameter tuner (with SageMaker Hyperparameter Tuning), access to foundation models (with SageMaker Jumpstart), hosting the model (with SageMaker real-time endpoint) and performing model inference using the endpoint. The Stable Diffusion model deployment will be done programmatically from the notebook.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

