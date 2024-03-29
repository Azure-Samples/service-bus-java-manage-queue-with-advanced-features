---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Servicebus
  platforms: java
---

# Getting Started with Servicebus - Service Bus Queue Advance Features - in Java #


  Azure Service Bus basic scenario sample.
  - Create namespace.
  - Add a queue in namespace with features session and dead-lettering.
  - Create another queue with auto-forwarding to first queue. [Remove]
  - Create another queue with dead-letter auto-forwarding to first queue. [Remove]
  - Create second queue with Deduplication and AutoDeleteOnIdle feature
  - Update second queue to change time for AutoDeleteOnIdle.
  - Update first queue to disable dead-letter forwarding and with new Send authorization rule
  - Update queue to remove the Send Authorization rule.
  - Get default authorization rule.
  - Get the keys from authorization rule to connect to queue.
  - Send a "Hello" message to queue using Data plan sdk for Service Bus.
  - Delete queue
  - Delete namespace
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/service-bus-java-manage-queue-with-advanced-features.git

    cd service-bus-java-manage-queue-with-advanced-features

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
