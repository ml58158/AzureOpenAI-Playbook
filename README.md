# AzureOpenAI-Playbook
Azure OpenAI Playbook created for Microsoft Sentinel

This playbook is designed to integrate Microsoft Sentinel with Azure OpenAI.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fml58158%2FAzureOpenAI-Playbook%2Fmain%2Fazuredeploy.json)

Requirements:

1. Azure OpenAI (Deployed from Azure subscription)
2. Microsoft Sentinel SIEM Solution

(If you need Azure OpenAI, please follow the directions on the Setup page.)

In order to use it, you will need to change the following variables:

<b>Azure OpenAI API Key:</b> Your Azure OpenAI API Key<br>
![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/284542ec-2e90-4f40-b9bd-db67f4a8181c)


<b>Azure OpenAPI URL Endpoint:</b> This is your deployment link for Azure OpenAI.<br>
![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/83e6b402-f5a4-4eef-9c46-8771ec25b170) <br>
(Example: https://myopenai.openai.azure.com/openai/deployments/Chat-GPT/chat/completions?api-version=2023-03-15-preview")

You need to replace the <myopenai> variable with your endpoint. 

![image](https://github.com/ml58158/AzureOpenAI-Playbook/assets/11156002/ee7f7cf0-4b97-42b4-8d46-1dc2ee04a371)

                            

