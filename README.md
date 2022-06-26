
### Deploy a High-Availability Web App using CloudFormation

This is a project called Udagram App where i deployed web servers for a highly available web app using CloudFormation. I wrote the script to create, update, deploy and delete the infrastructure and application for the project from scratch. The script began by defining the parameters to accept, definining the resources (VPC, Internet gateways, S3 bucket policy, NAT gatways, private and public subnets, route tables, security groups, launch configuration, load balances and listeners).

### Project Content

```
stack.yaml - it contains the main script for deploying the infrastructure
stack-parameters.json - it contains the parameters for deploying the infrastructure
create.sh - it contains the aws cli script to create the cloudformation stack
update.sh - it contains the aws cli script to update the cloudformation stack
delete.sh - it contains the aws cli script to delete the cloudformation stack
validate.sh - it contains the aws cli script to validate the deployment script
Udagram-Cloud-Arch.png - this is the cloud architecture diagram that the deployment script (stack.yaml) interprets
screenshots/* - it's a folder that contains the necessary screenshots to show that all the processes were successful

```
Cloud Architecture Diagram

![Cloud-architecture-diagram](https://raw.githubusercontent.com/SirPhemmiey/cloud-devops-project/master/Udagram-Cloud-Arch.png)
