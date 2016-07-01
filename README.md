---
services: azure-resource-manager
platforms: java
author: alvadb
---

#Getting Started with Resources - Manage Resource Group - in Java #


  Resource: Manage Resource Sample (for 1.0.0-beta2) - demonstrates how to perform common tasks using the Microsoft Azure Resource management service.
   - Create a resource group
   - Update a resource group
   - Create another resource group
   - Export an ARM template
   - List resource groups
   - Delete a resource group.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/resources-java-manage-resource-group.git

    cd resources-java-manage-resource-group

    mvn clean compile exec:java

## More information ##

[http://azure.com/java] (http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.