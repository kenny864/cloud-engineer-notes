# Making the web server work
Here are the general steps used to make a web server using aws and ec2

## Launch Instance
- In AWS->ECS, click launch instance.
- Go to security group use a security group with SSH port 22 and http port 80
- Launch Instance then click connect.

## Connect via SSH
- In connect menu, get the command line code to ssh into the aws client.

## Start Web Server with Apache
- Install Apache
- Start the httpd web server
- Enable the httpd web server
- Get the dns public id from AWS website

## Start Web Server with Nginx
- Install nginx
- Start nginx server
- get the ip from AWS EC2 page

## nginx bash commands
- Install nginx
sudo dnf install nginx -y

- Start nginx server
sudo systemctl start nginx

- Stop nginx server
sudo systemctl stop nginx

- Get status nginx server
sudo systemctl status nginx

## Best Practice
- terminate instance after you finish
