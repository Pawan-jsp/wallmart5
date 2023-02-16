provider "aws" {
  region     = "us-east-1"
  access_key = "AKIAZCUIUJN45ZAQSCMR"
  secret_key = "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"
}

rcsource "aws_instance" "Amazon Linux 2"{
  ami             = "ami-0dfcb1ef8550277af"
  instance_type   = "t2.micro"
  security_groups = ["launch-wizard-4"]
  key_name        = "mykey"
  tags = {
    Name = "RedHat Terraform Script - LINUX"
  }

}

resource "aws_instance" "RedHat"{
  ami             = "ami-0c9978668f8d55984"
  instance_type   = "t2.micro"
  security_groups = ["launch-wizard-3"]
  key_name        = "devopsgit"
  tags = {
    Name = "RedHat Terraform Script - ami"
  }

}
