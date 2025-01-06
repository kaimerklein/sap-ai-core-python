# Creating a Large Language Model Deployment in the Generative AI Hub of SAP AI Core on SAP BTP

Find a detailed explanation and tutorial in my [YouTube video](https://youtu.be/neFqIs28nI8)

<iframe width="560" height="315" src="https://www.youtube.com/embed/neFqIs28nI8?si=wuN4lns_DaZZ00zW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Pre-requisites

- Have [python](https://www.python.org/downloads/) installed
- Be able to work with [Jupyter notebooks](https://jupyter.org/install). My preferred option is to use [Microsoft's VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter).
- Create an instance of SAP AI Core in your BTP sub-account: [documentation](https://help.sap.com/docs/sap-ai-core/sap-ai-core-service-guide/initial-setup?locale=en-US)
- Find information about available LLM's in [SAP Note 3437766](https://me.sap.com/notes/3437766)
- Optionally, have the [Cloud Foundry CLI installed](https://docs.cloudfoundry.org/cf-cli/install-go-cli.html)

## LLM Deployment

See [deploy-llm.ipynb](deploy-llm.ipynb)

## LLM Consumption for Testing

See [consume-llm.ipynb](./consume-llm.ipynb)
