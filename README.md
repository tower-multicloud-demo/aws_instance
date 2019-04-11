--
scope: stackdemo
ec2_count: "1"
ec2_region: "eu-central-1"
ec2_size: "t2.micro"
ec2_ami: "ami-09de4a4c670389e4b"
ec2_key_name: "grieger_ec2"
ec2_sg: "demogroup"
vpc_subnet_id: subnet-idididid
ec2_assign_public_ip: true
ec2_wait: true
ec2_instance_tags:
  Name: "{{ scope }}"
  group: webservers
