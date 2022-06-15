# Weather2Comments

This Playbook takes the IP address supplied through the Analytics Rule and retreives the GEO location information from IP-API. It places the city, country, and IP address in the Comments section of the Microsoft Sentinel Incident instead of the Tags.

It then utilizes the API from WeatherAPI.com (a free API key for a certain number of uses) and retrieves the current weather conditions.

See <a href="pendingurl" target="_blank">How to Add Weather data for IP Addresses to a Microsoft Sentinel Incident</a> for more information.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frod-trent%2FSentinelPlaybooks%2Fmaster%2FWeather2Comments%2Fazuredeploy.json)
[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frod-trent%2FSentinelPlaybooks%2Fmaster%2FWeather2Comments%2Fazuredeploy.json)

