# ScheduledIncidentEmail

This Logic App queries the Log Analytics workspace for Azure Sentinel and then generates an email that delivers every morning at 7am. The email contains TimeGenerated, Title, Description, Severity, IncidentUrl.

See <a href="https://secureinfra.blog/2020/08/04/azure-sentinel-sending-an-email-each-morning-with-the-list-of-daily-incidents-created/">Azure Sentinel: Sending an Email Each Morning with the List of Daily Incidents Created</a> for more information.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frod-trent%2FSentinelPlaybooks%2Fmaster%2FScheduledIncidentEmail%2Fdailyincident.json)
[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frod-trent%2FSentinelPlaybooks%2Fmaster%2FScheduledIncidentEmail%2Fazuredeploy.json)
