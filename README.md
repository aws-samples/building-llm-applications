##  Building Large Language Models Applications Workshop

Associated workshop: https://catalog.us-east-1.prod.workshops.aws/workshops/5779400a-9bff-41c5-9f2c-2dcc8b71a374

This step by step workshop guidance is to educate ourselves on the foundation of prompt engineering and building chat assistant. It focuses on the basics of using the tools available e.g. Langchain, using retrieval augmented generation (RAG) to bring our own knowledge base into the prompt for the large language model (LLM), and using LLM to understand intent and extract information to be stored into an RDBMS database. It also touches on fine tuning a stable diffusion model to bring a logo into images e.g. MyCompanyLogo on painting on a wall. We will leverage Amazon SageMaker for the development environment (with SageMaker Studio), training job (with SageMaker Training Job), hyperparameter tuner (with SageMaker Hyperparameter Tuning), access to foundation models (with SageMaker Jumpstart), and hosting the model (with SageMaker real-time endpoint). We will use Falcon-7b-instruct for the LLM.

To start please follow the steps provided in the associated workshop link above. Lab 1 is about text generation while Lab 2 is about image generation. For Lab 1, you will first need to deploy the Falcon 7b Instruct model through SageMaker Jumpstart. Instruction is provided on the associated workshop page. Then you can follow the notebooks provided in the Lab 1 folder. For Lab 2, you can follow the notebook on the Lab 2 folder. The Stable Diffusion model deployment is done programmatically from the notebook.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

