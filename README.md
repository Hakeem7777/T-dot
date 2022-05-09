# T-dot
module "my_ec2_instance" {
 

  ec2_instance_type   = "t3.micro"
  ec2_instance_name   = "My instance"
  number_of_instances = 1
  ec2_ami_id          = < The AMI that you use to launch the instance>
}
