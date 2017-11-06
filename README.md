AWS CFN Basic ASG + LB + VPC
=========================

 - demo-vpc.yaml - basic VPC 
 - demo-nlb.yaml - generic Network Load Balancer
 - demo-iam.yaml - role for EC2 instances to access S3
 - demo-asg.yam - basic Launch Configuration and Autoscaling group, which attaches to the Load Balancer target group.

Instructions
---------------

 1. Open AWS Cloudformation console 
 2. Create your VPC stack using 'demo-vpc.yaml'
 3. Create a Network Load Balancer stack using 'demo-nlb.yaml' or create an Application Load Balancer stack using 'demo-alb.yaml'
 4. Create the EC2 IAM role stack using 'demo-iam.yaml'
 5. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NDY4MjE5NjNdfQ==
-->