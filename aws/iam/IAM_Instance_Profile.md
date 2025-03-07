# IAM Instance Profile for EC2

## Create Instance Profile

![ec2-instance-profile](images/1-ec2-instance-profile.png)


## Attach SSM Permission for Connecting to EC2

![role-permission1](images/2-role-permission1.png)


## Attach Full S3 Permission for S3 Operations

![role-permission2](images/3-role-permission2.png)


## Review the Role

![review-role](images/4-review-role.png)


## Created Role

Note that the IAM role also has IAM instance profile

![created-role](images/5-created-role.png)


## EC2 with Instance Profile 

![ec2-with-instance-profile](images/6-ec2-with-instance-profile.png)


## Install AWS CLI in EC2

![install-aws-cli](images/7-install-aws-cli.png)


## Create a S3 Bucket from AWS Console

![create-s3-bucket](images/8-create-s3-bucket.png)


## Copy a file to S3 Bucket from EC2 without AWS Credentials

In this screenshot, you can see the file copied to a S3 bucket without any credentials configured.

This is possible because we have attached, S3 full permission IAM policy during the EC2 instance profile creation.

![ability-to-copy-file-to-s3-bucket](images/9-ability-to-copy-file-to-s3-bucket.png)


## Create a S3 Bucket from CLI

In this screenshot, you can see the bucket being created from EC2

![create-bucket-from-cli](images/10-create-bucket-from-cli.png)
