   provider "aws" {
   region  = "us-central1"
   }
 resource "aws_instance" "web" {
  ami           = "ami-0a3c3a20c09d6f377"
  instance_type = "t2.micro"
  keypair       = "Nanna"
 }

