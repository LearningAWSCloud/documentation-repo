# IAM STS Assume Role

## Create assume role

As a first step, create a IAM role that has permission for full EC2 access 

![iam-dashboard](images/1-iam-dashboard.png)

![create-role](images/2-create-role.png)

![assign-ec2-permission](images/3-assign-ec2-permission.png)

![create-role-red](images/4-create-role-red.png)

## Switch Role

Now, login to red role from cloud_user

![switch-role](images/5-switch-role.png)

![switch-role-2](images/6-switch-role-2.png)

## Validate Permissions

After switching to red role, we are validating red roles privileges to create EC2

![launch-ec2](images/7-launch-ec2.png)

![ec2-launched](images/8-ec2-launched.png)

Now we can verify, red roles lack of permission for other services like CloudTrail

![access-denied](images/9-access-denied.png)
