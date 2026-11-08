# Azure-Cloud-Deployment

##Project Overview 

I decided to integrate my personal website/portfolio with a CI/CD pipeline through Github Actions and Azure Deployment Center in order to expedite my workflow. Having the ability to commit changes immediately to my web application with a simple git push is seamless and provides useful documentation for every build and deployment. This integration felt especially useful as it was also a solid introduction to using GitHub and becoming familiar with navigating some of the features Azure has to offer. 

##Technology Used
 Microsoft Azure
- Azure App Service
- GitHub Actions
- Git
- YAML
- C#
- ASP.NET MVC
- CI/CD

##Deployment Process
1. Push code to GitHub.
2. GitHub Actions detects the push.
3. Application dependencies are restored.
4. Application is built and published.
5. GitHub Actions deploys the application to Azure.
6. Azure App Service hosts the updated application.

##CI/CD Implementation

The pipeline automates:
- Download source code to GitHub Actions
- Download the NuGet packages and libraries
- Application build
- Azure deployment

##Github Actions Workflow

The automated deployment workflow code is defined in:
[View Azure Deployment Workflow](.github/workflows/azure-deploy.yml)
