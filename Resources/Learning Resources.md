[ARM Deploy templates](https://github.com/gottagetgit/ARMDeploy)

### To Search for the command in the cli

`Get-Command *<Search criteria>*`

Example:

`Get-Command *AZWebApp*`

### Creating a new Resource group

`New-AzResourceGroup -Name "ResourceGroupName" -Location "EastUS"`

### Creating a new App Service

`New-AzAppServicePlan -ResourceGroupName "<Groupname>" -Name "<Name>" -Location "EastUs" -Tier "Free"`
