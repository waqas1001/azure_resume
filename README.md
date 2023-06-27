# azure_resume_project
 

![azure_resume_project](https://github.com/waqas1001/azure_resume/assets/22656829/14ed69c3-6714-48df-bdf4-14d7c5fd4574)

# Prerequisites
+ Azure account
+ GitHub account
+ A domain from any DNS provider
+ A text editor like Visual Code 
+ Azure Functions Visual Code extensions

 # Overview 

 The aim of this project is 
 1. To host [static resume website](https://developer.mozilla.org/en-US/docs/Web/JavaScript) on azure storage
 2. Add a "vistor counter" functionality to the website
 3. Visitor Counter should communicate to the backend (CosmosDB) via an API call (Azure Fucntion)
 4. Implement a CI/CD pipeline using github actions that ensures continous integration and deployment.

   # Steps
   
 1. Create a github repo, clone it locally and create your website inside your repo 
 2. Webpage can be made from scratch using HTML and CSS, However you can also use a pre exisiting template.
    [Here is the one i used](https://styleshout.com/free-templates/ceevee/)
 3. Add a visitor counter for your website using [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
 4. Visitor counter code should communicate with the backend (CosmosDB) using API calls using [Azure Function](https://learn.microsoft.com/en-us/azure/azure-functions/functions-overview?pivots=programming-language-csharp)
 5. For the backend database, you can use [Azure CosmsDB](https://learn.microsoft.com/en-us/azure/cosmos-db/introduction)
 6. You need to allow [Integration between CosmosDb and Azure functions via bindings](https://learn.microsoft.com/en-us/azure/azure-functions/functions-bindings-cosmosdb-v2?tabs=in-process%2Cfunctionsv2&pivots=programming-language-csharp#add-to-your-functions-app)
 7. [Host the website on Azure blob storage](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website)
 8. Next, Enable HTTPS and custom domain support, Make use of [Azure CDN for this part](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-custom-domain-name?tabs=azure-portal#map-a-custom-domain-with-https-enabled)
 9. Create a Ci/CD pipeline using [Github Actions](https://docs.github.com/en/actions/quickstart) So anytime a change is made to the frontend, it gets automatically deplyed.
 10. You can also intergrate Iac tools to provision your infrastructure automatically. 

  # Conclusion 

  This is a begginer friendly project that lets you get hands on with a variety of cloud native services. I would recommend anyone intrested in learning the basics of cloud computing to try this project. 

    
    
    
 
