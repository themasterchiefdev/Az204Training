[ARM Deploy templates](https://github.com/gottagetgit/ARMDeploy)

### To Search for the command in the cli

`Get-Command *<Search criteria>*`

Example:

`Get-Command *AZWebApp*`

### Creating a new Resource group

`New-AzResourceGroup -Name "ResourceGroupName" -Location "EastUS"`

### Creating a new App Service

`New-AzAppServicePlan -ResourceGroupName "<Groupname>" -Name "<Name>" -Location "EastUs" -Tier "Free"`

### Creating a new webapp.

Note: AppServicePlan is the previous command.

`New-AzWebApp -ResourceGroupName "<resourcegroupname>" -Name "<webappname>" -Location "EastUS" -AppServicePlan "<appserviceplan>"`

### AZ Cli

`az group create --name cliwebapp --location eastus`

`az appservice plan create -g <previousgroup> -n <name>`

`az webapp create -g <previousgroup> -n "<name>" -p "<plan>"`

### AZ Web up usage

Sample repo link : https://github.com/Azure-Samples/html-docs-hello-world
clone link : https://github.com/Azure-Samples/html-docs-hello-world.git

````mkdir newwebapp

ls -al

cd newwebapp

git clone https://github.com/Azure-samples/html-docs-hello-world.git

ls -al

cd html-docs-hello-world

az webapp up --location eastus --name newwebapp1279 --html```
````
