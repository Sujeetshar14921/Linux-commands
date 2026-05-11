# Linux Commands CheatSheet

A complete collection of the most commonly used Linux commands in DevOps, Server Management, Cloud, and CI/CD workflows.

---

# 🚀 Most Used Linux Commands

# 📂 File & Directory Commands

## Check Current Directory

```bash
pwd
```

### 📌 Use For
- Show current working directory
- Navigation in terminal

---

## List Files & Folders

```bash
ls
```

### 📌 Use For
- View files and directories

---

## Detailed File List

```bash
ls -la
```

### 📌 Use For
- Show hidden files
- Check permissions

---

## Change Directory

```bash
cd folder-name
```

### 📌 Use For
- Move between folders

---

## Go Back One Folder

```bash
cd ..
```

### 📌 Use For
- Return previous directory

---

## Create Folder

```bash
mkdir project
```

### 📌 Use For
- Create new directories

---

## Remove Folder

```bash
rm -r folder-name
```

### 📌 Use For
- Delete folders recursively

---

## Create File

```bash
touch file.txt
```

### 📌 Use For
- Create empty files

---

## Delete File

```bash
rm file.txt
```

### 📌 Use For
- Remove files

---

## Copy File

```bash
cp file.txt backup.txt
```

### 📌 Use For
- Create backups
- Duplicate files

---

## Move/Rename File

```bash
mv old.txt new.txt
```

### 📌 Use For
- Rename files
- Move files

---

# 📄 File Reading Commands

## Read File Content

```bash
cat file.txt
```

### 📌 Use For
- View complete file

---

## Read Large File

```bash
less file.txt
```

### 📌 Use For
- Scroll large logs/files

---

## View First Lines

```bash
head file.txt
```

### 📌 Use For
- Check file start

---

## View Last Lines

```bash
tail file.txt
```

### 📌 Use For
- Monitor logs

---

## Live Log Monitoring

```bash
tail -f app.log
```

### 📌 Use For
- Real-time log monitoring
- Production servers

---

# 🔍 Search Commands

## Search File

```bash
find . -name "file.txt"
```

### 📌 Use For
- Locate files

---

## Search Text Inside Files

```bash
grep "error" app.log
```

### 📌 Use For
- Find logs/errors

---

## Search Running Process

```bash
ps aux | grep nginx
```

### 📌 Use For
- Check running services

---

# ⚙️ System Commands

## Check Running Processes

```bash
ps aux
```

### 📌 Use For
- Process monitoring

---

## Real-Time System Monitor

```bash
top
```

### 📌 Use For
- CPU/RAM monitoring

---

## Better System Monitor

```bash
htop
```

### 📌 Use For
- Advanced monitoring

---

## Check Disk Usage

```bash
df -h
```

### 📌 Use For
- Storage monitoring

---

## Check Folder Size

```bash
du -sh folder-name
```

### 📌 Use For
- Analyze storage usage

---

## Check Memory Usage

```bash
free -h
```

### 📌 Use For
- RAM monitoring

---

# 👤 User Management Commands

## Current User

```bash
whoami
```

### 📌 Use For
- Check logged-in user

---

## Switch User

```bash
su username
```

### 📌 Use For
- Change user account

---

## Run as Root

```bash
sudo command
```

### 📌 Use For
- Admin access

---

# 🌐 Network Commands

## Check IP Address

```bash
ip a
```

### 📌 Use For
- Network troubleshooting

---

## Ping Server

```bash
ping google.com
```

### 📌 Use For
- Internet connectivity check

---

## Check Open Ports

```bash
netstat -tulnp
```

### 📌 Use For
- Server debugging

---

## Download File

```bash
wget <url>
```

### 📌 Use For
- Download packages/files

---

## API Request

```bash
curl <url>
```

### 📌 Use For
- Test APIs
- DevOps automation

---

# 🔐 Permission Commands

## Change File Permission

```bash
chmod 755 file.sh
```

### 📌 Use For
- Make scripts executable

---

## Change File Owner

```bash
chown user:user file.txt
```

### 📌 Use For
- Ownership management

---

# 📦 Package Management Commands

## Update Packages (Ubuntu)

```bash
sudo apt update
```

### 📌 Use For
- Refresh package list

---

## Install Package

```bash
sudo apt install nginx
```

### 📌 Use For
- Install software

---

## Remove Package

```bash
sudo apt remove nginx
```

### 📌 Use For
- Uninstall software

---

# 🐳 DevOps & Server Commands

## SSH into Server

```bash
ssh user@server-ip
```

### 📌 Use For
- Remote server access

---

## SCP File Transfer

```bash
scp file.txt user@server:/path
```

### 📌 Use For
- Transfer files to server

---

## Check Docker Containers

```bash
docker ps
```

### 📌 Use For
- Monitor containers

---

## Kubernetes Pods

```bash
kubectl get pods
```

### 📌 Use For
- Kubernetes management

---

# 🔥 Most Used Linux Commands in DevOps

```bash
ls -la
cd
pwd
cat
tail -f
grep
find
top
htop
df -h
free -h
sudo
ssh
curl
wget
chmod
chown
ps aux
netstat -tulnp
```

---

# ⚡ Common DevOps Workflow

```bash
ssh user@server-ip
cd project
git pull origin main
docker compose up -d
tail -f logs/app.log
```

---

# 📌 Why This Repository?

Useful for:

- DevOps Engineers
- Cloud Engineers
- Linux Beginners
- Backend Developers
- Server Administrators
- CI/CD Learning

---

# ⭐ Support

If this repository helped you, give it a ⭐ on GitHub.

---

# 👨‍💻 Author

Sujeet Sharma
