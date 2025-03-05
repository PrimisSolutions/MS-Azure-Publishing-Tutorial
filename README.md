# ASP.NET Core - Azure Publishing Tutorial
This application is the application created at the end of the MS guided learning on ASP.NET Core for publishing applications (optionally, publishing to Azure). It is considered beginner-level knowledge and is presented here for anyone interested in the course.

The tutorial can be found here: [MS Learning](https://learn.microsoft.com/en-gb/training/modules/publish-aspnetcore-app/)

You can find the deployed app here, but as it is deployed on a Free tier, it is very likely the page will not load: [Azure Publishing Tutorial](https://azurepublishingtutorial.azurewebsites.net/)

![An image showing a webpage displaying 'Hello World' text.](https://github.com/PrimisSolutions/MS-Azure-Publishing-Tutorial/blob/master/images/Deployed%20Website.png)

## Purpose
The purpose of the ASP.NET apps published by Primis Solutions is to demonstrate to viewers the level of proficiency of the developers at the company.

This repository is considered beginner-level, and is provided purely for completeness.

## Lessons Learned
MS Learning does not always fully cover the requirements to set up your Azure account to allow the tutorial steps to happen. For example, a user attempting to deploy their app as an Azure Web App may encounter this error:
> The subscription is not registered to use namespace 'Microsoft.OperationalInsights'. See https://aka.ms/rps-not-found for how to register subscriptions.

![An image showing error text in VSCode describing a "Not Found" error for a resource called Operational Insights](https://github.com/PrimisSolutions/MS-Azure-Publishing-Tutorial/blob/master/images/Resource%20Error.png)

This is fairly straightforward to diagnose but a new user may be puzzled. The solution is to navigate to the Azure Subscription item in Azure and open "Resource Providers" under "Settings", then to find the resource and click the "Register" button.

![An annotated image from Azure showing the pathway to access Resource Providers and register them](https://github.com/PrimisSolutions/MS-Azure-Publishing-Tutorial/blob/master/images/Operational%20Insights%20Annotated.png)


### Tips
* Azure provides $200 of free credit for new accounts, and if this runs out there is still always a Free tier of Web App available that offers 60 minutes of CPU time (uptime) per day. This is ideal for testing and prototyping small-scale or greenfield projects.
