provider "aws" {
 region = "us-west-1"
 access_key = "AKIA4HO32YSPVFXS5RPZ"
 secret_key = "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"
}
resource "aws_instance" "ganesh" {
 ami = "ami-0cbd40f694b804622"
 instance_type = "t2.micro"
 count = 2
tags = {
        Name = "ganesh-instance"
}
}
