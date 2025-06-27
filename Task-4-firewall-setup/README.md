# 🔐 Task 4 - Firewall Setup using UFW on Linux (Kali)

### 🎯 Objective:
To configure and test basic firewall rules using **UFW** (Uncomplicated Firewall) on a Linux system.
This task involves blocking and allowing specific ports and understanding how firewalls manage network traffic.

---

## commands used 

```bash
# 1. Check if firewall is active
sudo ufw status

# 2. Enable UFW (Uncomplicated Firewall)
sudo ufw enable

# 3. Check firewall rules in numbered format
sudo ufw status numbered

# 4. View detailed status with logging info
sudo ufw status verbose

# 5. Block Telnet (insecure) port 23
sudo ufw deny 23

# 6. Allow SSH access (secure login) on port 22
sudo ufw allow 22

# 7. Allow HTTP (web traffic) on port 80
sudo ufw allow 80

# 8. Allow HTTPS (secure web traffic) on port 443
sudo ufw allow 443
