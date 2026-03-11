# Git Setup & GitHub Integration
This module covers the essential first steps

## 1. Installation on Linux
To install Git on Ubuntu
```bash
sudo apt update
sudo apt install git -y
```
![Git installation](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/fig1.png)

## 2. SSH Key Generation
Generate a new SSH key to securely connect to GitHub without typing your password every time:
```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```
![ssh key gen](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/sshgen.png)

Go to ssh key location (.ssh)
![ssh key location](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/sshkeylocation.png)

Copy pub key
![copy key](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/copypubkey.png)

## 3. Integrating with GitHub
Go to GitHub Settings > SSH and GPG keys > New SSH Key.
![integrate github](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/integrateingithub.png)

## 4. Paste pub key & Add
![paste key](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/pastepubkeyingithub.png)

## 5. Integrated
![integrated](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/integrated.png)

## 6. Connect through Linux
![connect](https://raw.githubusercontent.com/rajkumargdev/workshop_pics/main/integrated.png)

**Done! ✅**

---
**Author: RAJKUMAR GAALI**  
*Cloud Engineer | DevOps*
