# Terraform AWS EC2 Demo Module
Simple reusable EC2 module.

## Usage
```hcl
module "ec2" {
  source = "USERNAME/ec2-demo/aws"

  ami_id        = "ami-xxxxxxxx"
  instance_name = "demo-server"
}