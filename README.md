<<<<<<< HEAD
# terraform-aws-asg
###  This module is used to create ASG +  ELB. 
####  Please Use below code to create ASG

```
module "webapp" {
  source           = "ortacu/asg/aws"
  region           = "us-east-1"
  max_size         = "1"
  min_size         = "1"
  desired_capacity = "1"
  image_owner      = "xxxxx"
  instance_type    = "c5.large"
}
=======
# terraform-aws-asg
>>>>>>> 
