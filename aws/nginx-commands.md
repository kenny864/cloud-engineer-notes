# nginx bash commands

## Install nginx
- sudo dnf install nginx -y

## Start nginx server
- sudo systemctl start nginx

## Stop nginx server
- sudo systemctl stop nginx

## Get status nginx server.
- sudo systemctl status nginx
- active(running): means it's running
- active(dead): means it's stopped running
- loaded: enabled;: means it auto runs on boot
- loaded: disabled;: means it will not auto run on boot (default setting)

## Restart Service (breaks active connections)
- sudo systemctl restart nginx

## Reload Service (doesn't break active connections)
- sudo systemctl reload nginx
- applies configuration changes without dropping active connections
- safer and preferred method for routine updates

## Enable auto-start on Boot
- sudo systemctl enable nginx

## Disable auto-start on Boot
- sudo systemctl disable nginx

## Check auto-start status
- sudo systemctl is-enabled nginx

## Viewing All Running Services
- systemctl list-units --type=service
