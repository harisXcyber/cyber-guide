# 02 - Setup Your Hacking Lab 🛠️

> **Get your battle station ready in 30 minutes - everything you need, nothing you don't**

---

## 🎯 **What You'll Have After This Chapter**

✅ Professional hacking environment

✅ All essential tools installed

✅ Ready to start learning immediately

✅ Setup that scales with your skills

---

## 💻 **Your Minimum Requirements**

**Good News: You probably already have enough!**

**Minimum Specs:**
- Any laptop/desktop (Windows, Mac, Linux)
- 8GB RAM (4GB works, but slower)
- 50GB free space
- Internet connection

**That's it. Seriously.**

---

## 🔥 **Step 1: Get Kali Linux (Your Main Weapon)**

**Kali Linux = Operating system built for hackers**

**Contains 600+ hacking tools pre-installed**

### **Option A: VirtualBox (Recommended for Beginners)**

**Why VirtualBox?**
- Keeps your main system safe
- Easy to reset if you break something
- Can run multiple systems

**Steps:**

1. **Download VirtualBox**
   - Go to: `virtualbox.org`
   - Download for your OS
   - Install (keep clicking "Next")

2. **Download Kali Linux**
   - Go to: `kali.org/get-kali`
   - Choose "Virtual Machines"
   - Download "VirtualBox" version
   - File will be HUGE (3-4GB) - be patient

3. **Import Kali**
   - Open VirtualBox
   - Click "Import Appliance"
   - Select your downloaded Kali file
   - Click "Import" (takes 10-15 minutes)

4. **Start Your Hacking Lab**
   - Select Kali VM
   - Click "Start"
   - Default login: `kali` / `kali`

**🎉 BOOM! You now have a professional hacking setup!**

---

### **Option B: Dual Boot (Advanced Users)**

**Only do this if you're comfortable with computers**

**Steps:**
1. Create USB bootable drive with Kali
2. Boot from USB
3. Install alongside your main OS

**⚠️ Warning: Can break your computer if done wrong**

---

## 🌐 **Step 2: Essential Accounts (All FREE)**

### **TryHackMe Account**
- Go to: `tryhackme.com`
- Sign up (free)
- **This is where you'll learn everything**

### **GitHub Account**
- Go to: `github.com`
- Sign up (free)
- **Store your scripts and tools**

### **HackerOne Account**
- Go to: `hackerone.com`
- Sign up (free)
- **Your future bug bounty platform**

### **YouTube Account**
- Go to: `youtube.com`
- Sign up (free)
- **Best free learning resource**

---

## 🛠️ **Step 3: Essential Tools (Pre-installed in Kali)**

**Open Terminal in Kali and verify these exist:**

### **Network Tools**
```bash
nmap --version       # Network scanner
```

### **Web Application Tools**
```bash
burpsuite           # Web app testing
dirb --help         # Directory finder
```

### **System Tools**
```bash
metasploit-framework-console    # Exploitation framework
```

**If any don't work, run:**
```bash
sudo apt update && sudo apt upgrade -y
```

---

## 📝 **Step 4: Code Editor Setup**

**You need a good text editor for scripts**

### **Install VS Code in Kali:**
```bash
sudo apt update
sudo apt install code-oss -y
```

### **Essential Extensions:**
- Python
- Bash Debug
- Markdown Preview

---

## 🔧 **Step 5: Browser Setup**

**Install Firefox Extensions (Essential for Web Hacking):**

1. **FoxyProxy**
   - Manages proxy settings
   - Essential for Burp Suite

2. **Wappalyzer**
   - Identifies technologies
   - See what a website uses

3. **HackBar**
   - Quick payload testing
   - XSS and SQL injection helper

**Installation:**
- Open Firefox in Kali
- Go to `addons.mozilla.org`
- Search and install each extension

---

## 🎯 **Step 6: Verify Everything Works**

**Run this quick test:**

1. **Open Terminal**
2. **Run:**
   ```bash
   nmap scanme.nmap.org
   ```
3. **Should see scan results**

**If you see scan results = SUCCESS! 🎉**

---

## 📋 **Step 7: Organization Setup**

**Create these folders for organization:**

```bash
mkdir ~/hacking
mkdir ~/hacking/scripts
mkdir ~/hacking/notes
mkdir ~/hacking/tools
mkdir ~/hacking/targets
```

**This keeps everything organized from day 1**

---

## 🔥 **Common Setup Issues & Fixes**

### **Issue: Kali is Slow**
**Fix:** Allocate more RAM in VirtualBox settings (minimum 4GB)

### **Issue: Internet Not Working in VM**
**Fix:** Check VirtualBox network settings - use "NAT"

### **Issue: Screen Too Small**
**Fix:** Install VirtualBox Guest Additions

### **Issue: Copy/Paste Not Working**
**Fix:** Enable shared clipboard in VirtualBox settings

---

## ✅ **Setup Complete Checklist**

✅ Kali Linux running

✅ All accounts created

✅ Tools verified working

✅ Browser extensions installed

✅ Folders organized

✅ VS Code ready

**If you checked all boxes = You're ready to hack! 🚀**

---

## 🎯 **Pro Tips**

**💡 Tip 1:** Take a VM snapshot after setup
- VirtualBox → Snapshots → Take
- If you break something, restore instantly

**💡 Tip 2:** Update regularly
```bash
sudo apt update && sudo apt upgrade -y
```

**💡 Tip 3:** Join Discord communities
- Get help when stuck
- Learn from others
- Stay motivated

---

## 🚨 **Important Legal Note**

**ONLY use these tools on:**
- Your own systems
- TryHackMe/HackTheBox labs
- Systems you have written permission to test

**NEVER use on:**
- Other people's websites
- Company systems without permission
- Government systems

**This is the difference between ethical hacking and going to jail.**

---

## 🔗 **What's Next?**

**Your setup is complete!**

**Now let's learn the EXACT path to become a hacker.**

**[NEXT: Chapter 3 - The Learning Path →](03-learn-path.md)**

---

*"A professional is someone whose setup lets them focus on skills, not tools."*