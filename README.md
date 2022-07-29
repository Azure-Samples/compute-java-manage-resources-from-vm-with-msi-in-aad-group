---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Compute
  platforms: java
---

# Getting Started with Compute - Manage Resource From MSI Enabled Virtual Machine Belongs To AAD Group - in Java #


  Azure Compute sample for managing virtual machines -
    - Create a AAD security group
    - Assign AAD security group Contributor role at a resource group
    - Create a virtual machine with MSI enabled
    - Add virtual machine MSI service principal to the AAD group
    - Set custom script in the virtual machine that
           - install az cli in the virtual machine
           - uses az cli MSI credentials to create a storage account
    - Get storage account created through MSI credentials.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-resources-from-vm-with-msi-in-aad-group.git

    cd compute-java-manage-resources-from-vm-with-msi-in-aad-group

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
