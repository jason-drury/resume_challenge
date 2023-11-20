<!-- title: My joureny through the Cloud Resume Challenge --> 
[Cloud Resume Challenge][1]
============================

- [Cloud Resume Challenge](#cloud-resume-challenge)
  - [Introduction](#introduction)
    - [Week 0:](#week-0)
    - [Week 1:](#week-1)
    - [Week 2:](#week-2)
    - [Week 3:](#week-3)
    - [Week 4:](#week-4)
    - [Week 5+:](#week-5)
  - [How I heard about this challenge ie Notes](#how-i-heard-about-this-challenge-ie-notes)
  - [Thoughts while reading the Azure CRC handbook](#thoughts-while-reading-the-azure-crc-handbook)
  - [Points to talk about in an Inetrview](#points-to-talk-about-in-an-inetrview)
  - [Updates](#updates)
      - [09-10-2023](#09-10-2023)
  - [ToDo](#todo)


## Introduction

The Challenge:
### Week 0:
- [ ] 1. Certification - AZ-900 [Cloud Guru Resource][2] (at least prep/study)
### Week 1:
- [x] 2. Resume in HTML
- [x] 3. CSS - Resume styled with CSS coding
- [ ] 4. Deply website as [Static Website][3] in storage bucket
- [ ] 5. Use Azure CDN to implement HTTPS (SSL certificate securing traffic??)
- [ ] 6. Point custom DNS to Azure CDN endpoint for domain name.
### Week 2:
- [ ] 8. Use [Table API][4] of CosmosDB in [serverless capacity mode][5] to retreieve and update visitor count
- [ ] 9. Create an [API][6] to accept requests from webApp to communicate with DB. e.g Use [Azure Functions with an HTTP trigger][7]
- [ ] 10. Write Azure Function code in [Python][8]
- [ ] 13. Create a GitHub repo for the backend code for CI/CD
### Week 3: 
- [ ] 7. Use Javascript to display number of site visitors
- [ ] 11. Write [tests][9] for the Python code
### Week 4:
- [ ] 12. IaC - Define the Azure Function and CosmosDB API resources using an [Azure Resource Manager (ARM) Template][10] on a [Consumption plan][11]
- [ ] 14. CI/CD (Backend) - Set up [GitHub Actions][12] so updates to ARM template or python code trigger python tests to run, and on successful completion ARM app is packaged and deployed to Azure
- [ ] 15. CI/CD (Frontend) - Set up a second repo for website code. Set up Github Actions so new website code updates Azure storage blob automatically (May need to [purge Azure CDN endpoint in code][13] - DON'T commit Azure credentials)
### Week 5+:
- [ ] 16. Write [blog post][14] of what you have learnt

## How I heard about this challenge ie Notes
- Cooper White & Tim Youell 

Beginning with a bootstrap portfolio website to get started. Will need to customise the HTML/CSS styling to learn these properly / more after I have a basic version running online.

## Thoughts while reading the Azure CRC handbook
Where do I come from - astronomy 
Why the change - After 7.5 yrs of PhD research (4 self-funded), and over a decade at university I needed a change. 
Much of my self-learning through my PhD was based around communicating technical knowledge to people without the same background in the field, and around manipulating large amounts of data to identify and classify patterns

Where else are these skillsets relevant - Anywhere that data is collected and analysed. Particularly in business data analytics.

"open-ended projects that told me roughly the direction to go, then forced me to figure out how to achieve the objective as I went along" - this sounds like a PhD XD

"ability to pick up new things quickly, in a self-motivated way"


## Points to talk about in an Inetrview
- Full-stack software development (the static website and Python pieces)
  - **Notes here**:
- Version control (the Github piece)
  - **Notes here**:
- Infrastructure as code (the Azure Resource Manager (ARM) piece) 
  - **Notes here**:
- Continuous integration and delivery (connecting GitHub Actions, ARM, and Azure)
  - **Notes here**:
- Cloud services and “serverless” (Azure Functions, CosmosDB, Azure DNS, Azure Storage)
  - **Notes here**:
- Application security (Azure RBAC, CORS, API authentication/authorization)
  - **Notes here**:
- Networking, as in the way computers talk to each other (DNS, CDNs, the whole "cloud" thing)
  - **Notes here**:
- Networking, as in the way people talk to each other (the blog post, the Discord community - this is probably the highest-value step in the whole challenge because of the professional doors it can unlock for you, and we'll talk about that in more detail later on.)
  - **Notes here**: 





## Updates
#### 09-10-2023
- Began documentation of Cloud Resume Challenge progress. 
- Initialisation of Git Repo
- Update of page to include current portfolio project list


## ToDo

- [ ] Convert hardcoded page to Jekyll or alternative to implement yaml-based updates
- [ ] Update profile picture / styling to suit mobile / limited size displays
- [ ] Create new resume for profile
- [ ] Decrease size of certification badges to ~50\% of current size
- [ ] Add projects to portfolio and maintain updated list, rank by top 5 projects that receive interest based on article / blog post access statistics

[1]: http://www.cloudresumechallenge.com/ "Cloud Resume Challenge"
[2]: https://acloudguru.com/course/az-900-microsoft-azure-fundamentals "Cloud Guru AZ-900 course"
[3]: https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website "Azure Static Website as Storage Blob"
[4]: https://learn.microsoft.com/en-us/azure/cosmos-db/table/introduction "CosmosDB Table"
[5]: https://learn.microsoft.com/en-us/azure/cosmos-db/serverless "CosmosDB serverless"
[6]: https://medium.com/@perrysetgo/what-exactly-is-an-api-69f36968a41f "What is an API?"
[7]: https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook?tabs=isolated-process%2Cfunctionsv2&pivots=programming-language-csharp "Azure Functions HTTP webhook"
[8]: https://github.com/Azure/azure-sdk-for-python "Azure SDK for Python"
[9]: https://realpython.com/python-testing/ "Python Testing"
[10]: https://learn.microsoft.com/en-us/azure/azure-functions/functions-infrastructure-as-code?tabs=bicep "Azure functions as IaC"
[11]: https://learn.microsoft.com/en-us/samples/azure/azure-quickstart-templates/function-app-create-dynamic/ "Provision a function app on a Consumption plan"
[12]: https://docs.github.com/en/actions/learn-github-actions "GitHub Actions"
[13]: https://learn.microsoft.com/en-us/azure/cdn/cdn-purge-endpoint "CDN endpoint purge"
[14]: https://dev.to/ "DEV.to - Potential Blog site"