# ChatGPT-Sentinel

<b>Add Recommendations to Microsoft Sentinel Incidents from ChatGPT<br><br></b>
This Playbook sends the title and description of a Sentinel Incident to ChatGPT through the OpenAI API/Logic App and then writes the returned recommendations to the Incident's Activity Log pane.

An OpenAI API key is required: https://beta.openai.com/account/api-keys <br><br>

Even though it requests your API key during deployment, after deploying to Azure, you'll still need to make the API connection as shown:



[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frod-trent%2FSentinelPlaybooks%2Fmaster%2FChatGPT%2Fazuredeploy.json)
[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frod-trent%2FSentinelPlaybooks%2Fmaster%2FChatGPT%2Fazuredeploy.json)
