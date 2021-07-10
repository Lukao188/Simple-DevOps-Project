# Simple DevOps Project

[![Image](https://github.com/yankils/Simple-DevOps-Project/blob/master/Devops_course.PNG "DevOps Project - CI/CD with Jenkins Ansible Docker Kubernetes ")](https://www.udemy.com/course/valaxy-devops/?referralCode=8147A5CF4C8C7D9E253F)

This Repository is a collection of Implementation documents. 

### Purpose:
By following this repository you can able to setup a DevOps CI/CD Pipeline using
- git
- Jenkins
- Maven
- Ansible
- Docker &
- Kubernetes

# AWS Configuration
1. Remote into your EC2 instance.
`ssh -i <YOUR_PRIVATE_KEY_FILE>.pem <INTERNET_ADDRESS_OF_YOUR_INSTANCE>`
2. Add a "client-alive" directive to the instance's SSH-server configuration file.
`echo 'ClientAliveInterval 60' | sudo tee --append /etc/ssh/sshd_config`
3. Restart or reload the SSH server, for it to recognize the configuration change.
- The command for that:
`sudo service sshd restart`
4. Disconnect.
`logout`
