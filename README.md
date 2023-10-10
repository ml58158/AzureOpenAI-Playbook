# AzureOpenAI-Playbook
Azure OpenAI Playbook created for Microsoft Sentinel

This playbook is designed to integrate Microsoft Sentinel with Azure OpenAI and is a work in progress.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fml58158%2FAzureOpenAI-Playbook%2Fmain%2Fazuredeploy.json)

Requirements:

1. Azure OpenAI (Deployed from Azure subscription)
2. Microsoft Sentinel SIEM Solution (Deployed from Azure subscription as well)

(If you need Azure OpenAI, please follow the directions on the Setup page.)

In order to use it, you will need to change the following variables:

<b>Azure OpenAI API Key:</b> Your Azure OpenAI API Key<br>
![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/284542ec-2e90-4f40-b9bd-db67f4a8181c)

<b>Azure OpenAPI URI Endpoint:</b> This is your deployment link for Azure OpenAI.<br>
![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/83e6b402-f5a4-4eef-9c46-8771ec25b170) <br>
(Example: https://<myopenai>.openai.azure.com/openai/deployments/<deploymentname>/chat/completions?api-version=2023-03-15-preview")

You need to replace the <myopenai> variable with your endpoint and <deploymentname> with your model deployment name.

![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/ee7f7cf0-4b97-42b4-8d46-1dc2ee04a371)

To find these pieces of information, please see below:<br>
1. API Key and Endpoint URI<br>
*This is found in the Keys and Endpoint section on your Azure OpenAI deployment.* <br>
![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/a42db8e4-f9fe-4037-bb5c-cee6ba57a42c) <br>

2. Deployment Name <br>
*This is found inside Azure AI Studio when you setup your deployment.* <br>
![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/2c915ffe-4a23-4731-be96-bcd87315a36c)
