 # Linux Commands Used in This Project

This file documents the Linux commands used during the setup and hardening of the AWS EC2 server.

## Commands Used

```bash
# Update system packages
sudo apt update && sudo apt upgrade -y

# Install Nginx web server
sudo apt install nginx -y

# Start Nginx service
sudo systemctl start nginx

# Enable Nginx to start on boot
sudo systemctl enable nginx

# Check Nginx service status
sudo systemctl status nginx

# Check open ports on the server
sudo ss -tulnp

# Check firewall status
sudo ufw status

# Check Fail2Ban service status
sudo systemctl status fail2ban
```
