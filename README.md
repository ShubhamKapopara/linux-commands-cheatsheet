# 🐧 Linux-commands-cheatsheet
Master essential Linux commands with this well-structured cheat sheet! Perfect for quick reference and hands-on learning — from basic navigation to advanced operations, organized for faster recall and real-world application.

<!-- Image with clickable link to full size -->
<a href="https://github.com/ShubhamKapopara/linux-commands-cheatsheet/blob/main/Linux%20Commands.png">
  <img src="https://raw.githubusercontent.com/ShubhamKapopara/linux-commands-cheatsheet/main/Linux%20Commands.png" alt="Linux Commands Cheat Sheet" width="600">
</a>

## 🧑‍💻 Real-World Linux Commands 

These are commonly used Linux commands in **DevOps, Cloud, and System
Administration tasks** 

### 📂 File & Directory Management

``` bash
ls -la      # List all files with details
cd /path    # Change directory
pwd         # Print working directory
mkdir name  # Create new directory
rm -rf name # Remove directory/file recursively and forcefully
cp file1 file2   # Copy file
mv old new       # Move or rename file
```

### 📄 File Content & Search

``` bash
cat file.txt       # View file contents
less file.txt      # Scrollable view
head -n 20 file.txt # View first 20 lines
tail -f log.txt    # Live log monitoring
grep "error" file  # Search for keyword in file
find /path -name "*.log" # Find files by pattern
```

### ⚙️ System Monitoring & Process Management

``` bash
top            # Live process monitoring
htop           # Interactive process viewer
ps aux         # List running processes
kill -9 PID    # Kill process by PID
df -h          # Check disk usage
du -sh *       # Show size of each directory/file
free -h        # View memory usage
```

### 🌐 Networking & Connectivity

``` bash
ping google.com      # Test network connectivity
curl -I example.com  # Fetch HTTP headers
wget URL             # Download files
netstat -tuln        # List open ports
ss -tuln             # Alternative to netstat
```

### 👤 User & Permission Management

``` bash
whoami               # Current user
sudo su              # Switch to root
chmod 755 file       # Change permissions
chown user:group file # Change ownership
```

### 📦 Package Management (Debian/Ubuntu)

``` bash
sudo apt update      # Update package list
sudo apt upgrade     # Upgrade packages
sudo apt install pkg # Install a package
```

## 🤝 Community

We welcome feedback and contributions!  

- **Report Issues:** [Open an issue](https://github.com/ShubhamKapopara/linux-commands-cheatsheet/issues) to suggest improvements or report errors.  
- **Contribute:** Fork the repository, make your changes, and submit a pull request.  

Thank you for helping improve this Linux Commands Cheat Sheet! 🚀


