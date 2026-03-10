 # Linux Commands Used in This Project

## Update System

```bash
sudo apt update && sudo apt upgrade -y
```

## Install Nginx

```bash
sudo apt install nginx -y
```

## Start Nginx

```bash
sudo systemctl start nginx
```

## Enable Nginx

```bash
sudo systemctl enable nginx
```

## Check Nginx Status

```bash
sudo systemctl status nginx
```

## Check Open Ports

```bash
sudo ss -tulnp
```

## Check Firewall Status

```bash
sudo ufw status
```

## Check Fail2Ban Status

```bash
sudo systemctl status fail2ban
```
