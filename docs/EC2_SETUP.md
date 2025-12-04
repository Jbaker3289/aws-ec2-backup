EC2 Instance deployed with Apache web server
why: host web application that connects to a database
Instance details: t2.micro, Amazon Linux 2023, IP 16.170.211.119
Steps taken:

Launched EC2 instance
Connected via SSH
Installed Apache: sudo yum install httpd -y
Started service: sudo systemctl start httpd
Enabled autostart: sudo systemctl enable httpd
IP address tested and confirmed

Result: Web server accessible at http://16.170.211.119
