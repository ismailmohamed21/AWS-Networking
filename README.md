# ## ## AWS Networking Lab — EC2 and NGINX

### Project Overview

In this project, I launched an Ubuntu EC2 instance on AWS and configured it to host a web page using NGINX.

I started by launching the EC2 instance and checking the network configuration, including the route to the internet gateway. I configured the security group to allow HTTP traffic on port 80 and connected to the instance through AWS EC2 Instance Connect.

During the setup, I encountered connection issues when trying to access the instance through SSH. I troubleshot the security group rules and adjusted the SSH access configuration to restore connectivity. I also learned that Ubuntu uses `apt` to install packages, rather than `yum`, which is used by some other Linux distributions.

After resolving these issues, I updated the Ubuntu package list, installed NGINX, and enabled and started the service. I verified that NGINX was running using `systemctl status nginx` and tested the web server locally with `curl http://localhost`.

The final step was to test the website through a browser using the EC2 instance's public IP address.

### Technologies Used

AWS EC2, Ubuntu Linux, NGINX, AWS Security Groups, SSH, HTTP and basic networking.

### Project Screenshot

Add a screenshot of the NGINX Welcome page after confirming that it is accessible through the public IP address.



### <img width="870" height="531" alt="image" src="https://github.com/user-attachments/assets/b2845a96-1142-47d6-bf9c-810622a8d72e" />



