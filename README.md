# Flask in EC2 instances

Flask application powered by Waitress WSGI server to display a basic html website in an EC2 instance using NGINX to port forward HTTP calls to the html contents making it accessible to the internet from the EC2 public IP address.

The repo comes with configuration scripts for EC2 instance images for Amazon Linux, Ubuntu, and Windows. To use them, copy the script content inside the **User Data** section when creating the instance.

| AMI          | Script                                     |
| ------------ | ------------------------------------------ |
| Amazon Linux | [amazon.conf](./flask-nginx/amazon.conf)   |
| Ubuntu       | [ubuntu.conf](./flask-nginx/ubuntu.conf)   |
| Windows      | [windows.conf](./flask-nginx/windows.conf) |

---

# NGINX in EC2 instances

Display a basic html website in an EC2 instance using NGINX to port forward HTTP calls to the html contents making it accessible to the internet from the EC2 public IP address.

The repo comes with configuration scripts for EC2 instance images for Amazon Linux, Ubuntu, and Windows. To use them, copy the script content inside the **User Data** section when creating the instance.

| AMI          | Script                                    |
| ------------ | ----------------------------------------- |
| Amazon Linux | [amazon.conf](./nginx-only/amazon.conf)   |
| Ubuntu       | [ubuntu.conf](./nginx-only/ubuntu.conf)   |
| Windows      | [windows.conf](./nginx-only/windows.conf) |
