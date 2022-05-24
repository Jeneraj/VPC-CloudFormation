# VPC-CloudFormation
Deploys a VPC through CloudFormation


CloudFormation is an Infrastructure as Code (IaC) service within AWS. Infrastructure as Code is a way of building your architecture using a particular coding language where you deploy your applications using code written in either JSON or YAML. With IaC you can speed up your resource deployment, and CloudFormation will provision your resources in a safe, repeatable manner, allowing you to build and rebuild your infrastructure and applications without having to perform manual actions or risk misconfiguring something.

Here, We are launching an Apache Web server and create a simple web page for us to see:

These are the following resources I created through CloudFormation:

  -A VPC with a CIDR Block range of 10.0.0.0/16
  -An Internet Gateway
  -2 Public Subnets
  -2 Private Subnets
  -Route tables for the Subnets
  -A Security Group for a Web Server
  -An EC2 Instance
  
  After creation completed, the output section gives the Public Ip to launch the simple Apache Web Server.
