# terraform-aws-vpsoctober
```htl
module "vpc" {
    source = "AibikeKasym/vpsoctober/aws"
    version = "0.0.3"
    region = "us-east-2"
    vpc_cidr = "10.0.0.0/16"
    vpc_name = "aibike"
    subnet1_cidr = "10.0.1.0/24"
    subnet2_cidr = "10.0.2.0/24"
    subnet3_cidr = "10.0.3.0/24"
    instance_type = "t2.micro"
    key_name = "kaizen"
    type = true
}
```


