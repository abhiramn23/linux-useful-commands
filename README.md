# linux-useful-commands
this repo contians useful linux commands 
This repository contains a *concise PDF guide* documenting essential Linux commands for *system health monitoring, troubleshooting, user management, and basic security*.

## 📖 Contents
The guide covers:

### 1. System Information
- uname -a → Display kernel version and system info  
- hostnamectl → Show hostname and OS details  
- uptime → System uptime  

### 2. Resource Monitoring
- top / htop → Real-time CPU, memory, process monitoring  
- free -h → Memory usage  
- df -h → Disk space usage  
- du -sh /path → Directory size  

### 3. Process Management
- ps aux → List processes  
- kill -9 <PID> → Terminate process  
- systemctl status <service> → Service status  

### 4. Networking & Ports
- ip a → Show IPs and interfaces  
- ping <host> → Connectivity test  
- ss -tuln → Listening ports  
- netstat -tulnp → Active connections  

### 5. Logs & Troubleshooting
- journalctl -xe → System logs  
- dmesg | less → Kernel messages  
- tail -f /var/log/syslog → Live log monitoring  

### 6. User & Permission Management
- whoami → Current user  
- id → UID/GID info  
- chmod 600 file → Strict permissions  
- chown user:group file → Change ownership  

### 7. Security Basics
- ufw status / ufw enable → Firewall management  
- cat /etc/ssh/sshd_config | grep PermitRootLogin → Check SSH root policy  
- find / -perm -4000 -type f 2>/dev/null → Find risky SUID binaries  

---

## Files in Repo
- linux_system_health_guide.pdf → Full concise PDF guide  
- README.md → Overview of repository  

---

## How to Use
1. Clone this repo  
   ```bash
   git clone https://github.com/your-username/linux-system-health-guide.git
