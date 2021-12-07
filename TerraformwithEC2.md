provider "aws" {
access_key = "AKIA4C42SYVUS4XVHFEG"
secret_key = "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"
region = "us-east-1"
}
resource "aws_instance" "instance1" {
ami = "ami-05930ce55ebfd2930"
instance_type = "t2.micro"
tags = {
Name = "Centos-8-Stream"
}
}
