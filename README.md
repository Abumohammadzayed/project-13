# project-13
jenkins integrated github

  prvider "aws"{
   region      = "ap-south-1"
   acccess_key = "AKIAZQ7AS7FJXFBQKKGX"
   seceret_key = "OeU+OFUnsW3t7zZbk/02Nxtpz67WWKSZ7nOBMzh"
   }
   resurce "aws_instances" "server1" {
   ami = "ami-0756a1c858554433e"
   instance_type = "t2.micro"
   
   tags = {
    Name = Var. tag_name
     }
    }
