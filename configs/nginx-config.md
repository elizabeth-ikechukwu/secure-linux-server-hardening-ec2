# Nginx Configuration

This file documents the Nginx configuration used to serve the static portfolio website on the AWS EC2 instance.

## Configuration File Location

```
/etc/nginx/sites-available/default
```

## Server Block Configuration

```nginx
server {
    listen 80;
    server_name lizzycloudlab.online www.lizzycloudlab.online;

    root /var/www/html;
    index index.html index.htm;

    location / {
        try_files $uri $uri/ =404;
    }
}
```

## Test Nginx Configuration

```bash
sudo nginx -t
```

## Restart Nginx

```bash
sudo systemctl restart nginx
```
