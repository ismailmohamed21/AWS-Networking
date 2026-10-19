# ## AWS Networking Lab — EC2 and NGINX

### Project Overview

In this project, I launched an Ubuntu EC2 instance on AWS and configured it to host a web page using NGINX.

I started by launching the EC2 instance and checking the network configuration, including the route to the internet gateway. I then configured the security group to allow HTTP traffic on port 80 and connected to the instance using AWS EC2 Instance Connect.

Once connected, I updated the Ubuntu package list and installed NGINX using `apt`. I enabled and started the NGINX service, then checked its status to confirm that it was running correctly.

To test the setup, I used `curl http://localhost` in the terminal and verified that the NGINX welcome page was returned. The next step was to access the web server through a browser using the EC2 instance's public IP address.

### Technologies Used

AWS EC2, Ubuntu Linux, NGINX, AWS Security Groups, HTTP and basic networking.

### <img width="870" height="531" alt="image" src="https://github.com/user-attachments/assets/b2845a96-1142-47d6-bf9c-810622a8d72e" />



