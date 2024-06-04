Login to IBM Cloud
```
ibmcloud login --apikey <Your API Key Here>
```

List resource groups
```
ibmcloud resource groups
```
Target a resource group
```
ibmcloud target -g default
```

List services in the catalog
```
ibmcloud catalog service-marketplace
```

Service name: knowledge-studio
```
ibmcloud catalog service knowledge-studio
```

Create a service instalnce
```
ibmcloud resource service-instance-create "My-WKS" knowledge-studio free eu-de --allow-cleanup
```
## References
* https://cloud.ibm.com/docs/cli?topic=cli-ibmcloud_commands_resource
* https://cloud.ibm.com/docs/cli/reference/ibmcloud?topic=cli-ibmcloud_catalog
* https://cloud.ibm.com/docs/overview?topic=overview-locations
* https://cloud.ibm.com/docs/Cloudant?topic=Cloudant-creating-an-ibm-cloudant-instance-on-ibm-cloud-by-using-the-ibm-cloud-cli
