# jyothi-aws-project
This repository is about AWS projects
# AWS EC2 Commands

## Launch EC2 Instance

```bash
aws ec2 run-instances \
--image-id ami-xxxxxxxx \
--count 1 \
--instance-type t2.micro \
--key-name MyKeyPair \
--security-group-ids sg-903004f8 \
--subnet-id subnet-6e7f829e
