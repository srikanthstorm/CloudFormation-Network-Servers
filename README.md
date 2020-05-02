# CloudFormation-Network-Servers

This Code contains scripts to Create a Network along with VPC, Subnets, NAT Gateways, Applications Servers, Autoscaling groups and Loadbalancers

Before executing the script install aws-sdk in your machine followed by the step
```
aws configure

Load balancer url to test: http://serve-webap-1g7b32e6821l1-404427981.us-east-1.elb.amazonaws.com/
Region used: us-east-1
```
In order to run this script 

````
./create <stack-name> <scriptname> <parameterscriptname>

./update <stack-name> <scriptname> <parameterscriptname>

./delete <stack-name>

```
