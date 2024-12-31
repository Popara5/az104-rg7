# az104-rg7
Created a Resource Group in Microsoft Azure 
Step-by-Step Guide to Create a Resource Group in Azure
Sign in to the Azure Portal:

Go to Azure Portal and sign in with your Azure account.

Navigate to Resource Groups:

In the search bar, type "Resource groups" and select it from the list of services.

Create a Resource Group:

Click on the "Create" button to start creating a new resource group.

Configure the Basics:

Subscription: Select the subscription you want to use.

Resource Group: Enter a name for your resource group.

Region: Choose the region where you want to deploy the resources.

Add Tags (Optional):

You can add tags to help organize and manage your resources. Tags are key-value pairs that you can use to categorize resources.

Review and Create:

Click on "Review + Create" to review your settings.

Click on "Create" to finalize the creation of your resource group.

Verify the Resource Group:

Go to the "Resource groups" section to verify that your new resource group has been created


****If you are working with your own subscription take a minute to delete the lab resources. This will ensure resources are freed up and cost is minimized. The easiest way to delete the lab resources is to delete the lab resource group.
In the Azure portal, select the resource group, select Delete the resource group, Enter resource group name, and then click Delete.
Using Azure PowerShell,
Remove-AzResourceGroup -Name resourceGroupName.
Using the CLI,
# az group delete --name resourceGroupName.

