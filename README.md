# aws-ecs-ec2-cluster
A Cloudformation template for spinning up an ESC Cluster using EC2 instances. This template assume you have already created the VPC you want to use.


## Resourcces
This Cloud Formation will provision the following resources:

- LaunchConfig
- EC2
- Security Group for the EC2 instances
- AutoScalingGroup
- ALB (with the option to attach an SSL certificate)
- Target Group
- Security Group for the ALB
- ECS Cluster