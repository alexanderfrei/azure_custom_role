# Steps to create custom role
1. In Azure Subscription --> IAM --> Create custom role
2. Give a name for custom role 
3. In the permission page, click add permissions, type the path like Microsoft.Network/virtualNetworks/virtualNetworkPeerings and then choose Read and Write
4. Do step number 3 for all needed permission in the .json file
5. Assignable scope must be subscriptions
6. Review and Update
7. Go to VNets you want create peerings --> IAM --> Assign this custom role to your service principal 
8. Done