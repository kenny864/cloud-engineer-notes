# Managing Linux services with systemctl

## What restart vs start means
- restart breaks all active connection and starts it again
- start just starts a server that presumably is off

## Why auto-start matters for servers
- it ensures service persistence and high availbility by making the nginx web server start when the system reboots

## One command you think cloud engineers use most
- sudo systemctl restart nginx
- sudo systemctl status nginx
