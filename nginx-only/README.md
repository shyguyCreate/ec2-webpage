# Nginx-Only in EC2 instances

Display a basic html website in an EC2 instance using NGINX to port forward HTTP calls to the html contents making it accessible to the internet from the EC2 public IP address.

The repo comes with configuration scripts for EC2 instance images for Amazon Linux, Ubuntu, and Windows. To use them, copy the script content inside the **User Data** section when creating the instance.

| AMI          | Script                                             |
| ------------ | -------------------------------------------------- |
| Amazon Linux | [amazon.conf](/user-data/nginx-only/amazon.conf)   |
| Ubuntu       | [ubuntu.conf](/user-data/nginx-only/ubuntu.conf)   |
| Windows      | [windows.conf](/user-data/nginx-only/windows.conf) |
