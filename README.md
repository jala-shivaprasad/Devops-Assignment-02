AWS DevOps Engineer Intern Assignment

Create an EC2 Instance Steps :

 1.Logged in to the AWS Management Console.
 
 2.Launched an Ubuntu EC2 instance.
 
 3.Created a Security Group:
 
  Allowed:
   Port 22 (SSH)
   Port 80 (HTTP)
   
 4.Connected to the instance using SSH.
## Linux Commands Used

### 1. Update Package Repository

```bash
sudo apt update
sudo apt upgrade -y
```

Updates the package list and upgrades installed packages to their latest available versions.

---

### 2. Install Nginx

```bash
sudo apt install nginx -y
```

Installs the Nginx web server on the Ubuntu EC2 instance.

---

### 3. Start Nginx Service

```bash
sudo systemctl start nginx
```

Starts the Nginx web server.

---

### 4. Enable Nginx on Boot

```bash
sudo systemctl enable nginx
```

Configures Nginx to start automatically whenever the EC2 instance boots.

---

### 5. Check Nginx Status

```bash
sudo systemctl status nginx
```

Displays the current status of the Nginx service.

---

### 6. Restart Nginx

```bash
sudo systemctl restart nginx
```

Restarts the Nginx service after making configuration or website changes.

---

### 7. Check Disk Usage

```bash
df -h
```

Displays disk space usage in a human-readable format.

---

### 8. Check Memory Usage

```bash
free -h
```

Shows the system's RAM and swap memory usage in a human-readable format.

---

### 9. Check Running Processes

```bash
ps -ef
```

Lists all currently running processes.

Alternatively:

```bash
top
```

Displays real-time system resource usage and active processes.
