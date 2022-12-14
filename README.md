# Deploy-a-high-availability-web-app-using-CloudFormation
 
# How to deploy the server:

# first the netwrok
> ./create.sh NetworkStack Network/Network.yml Network/Network-params.json
# second step run the server cloudformation script
> ./create.sh ServersStack Servers/Servers.yml Servers/Servers-params.json
# For delete

> ./delete.sh ServersStack 
> ./delete.sh NetworkStack 