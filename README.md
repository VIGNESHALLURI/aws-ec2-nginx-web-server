# AWS EC2 Web Server Using Nginx

## Project

I created a simple web server using AWS EC2 and Nginx.

## AWS Services Used

- Amazon EC2
- Security Groups
- EC2 Instance Connect

## Tools Used

- Amazon Linux 2023
- Nginx
- Linux
- HTML

## What I Did

1. Created an EC2 instance.
2. Connected to the instance using EC2 Instance Connect.
3. Installed Nginx.
4. Started Nginx.
5. Created a simple HTML webpage.
6. Checked Nginx status.
7. Tested the server using curl.
8. Opened the webpage using the EC2 public IP.
9. Stopped the EC2 instance after testing.

## Testing

I used:

sudo systemctl status nginx

and:

curl -I http://localhost

The server returned:

HTTP/1.1 200 OK

## Result

My webpage was successfully running on an EC2 instance using Nginx.

## Architecture

Internet → EC2 → Nginx → HTML Page
