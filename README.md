# AWS DevOps Engineer Intern Assignment

## Objective
Deploy a simple website on an AWS EC2 instance using Nginx.

## AWS Services Used
- Amazon EC2
- Security Group

## Linux Commands Used

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
df -h
free -h
ps aux
```

## Steps Performed

1. Created an Ubuntu EC2 instance.
2. Configured Security Group (Ports 22 and 80).
3. Connected to EC2 using SSH.
4. Installed and started Nginx.
5. Created and hosted a custom HTML webpage.
6. Verified the website using the EC2 Public IP.

## Website

Access the website using the EC2 Public IP:

```
http://3.110.217.73
```

## Author

**Name:** Ashlesha Kamal
## Bonus Task: Docker Installation

### Commands Used

```bash
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
sudo docker run hello-world
```

### Result
Docker was installed successfully, and the `hello-world` container executed successfully.
