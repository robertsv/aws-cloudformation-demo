# aws-cloudformation-demo

AWS CloudFormation sample template to demo how to:
* create two EC2 instances in non-default VPC, where one is in public subnet and one in private subnet
* use CF init and UserData for bootstrapping


Following main resources are created:
* VPC
* two subnets
* two EC2 instances
* internet gateway
* NAT gateway
* one EIP

This template is to designed to work in all regions but it requires two input parameters:
* EC2 ssh access key
* AMI ID for Ubuntu 18

[![Analytics](https://ga-beacon.appspot.com/UA-54543878-3/robertsv/aws-cloudformation-demo)]()
