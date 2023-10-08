# Check out my tutorials

on [Medium](https://medium.com/@MonlesYen/list/python-for-cybersecurity-0772db1c4f69)

---

# Install VS Code in Kali

[Further info | Computing For Geeks](https://computingforgeeks.com/how-to-install-visual-studio-code-on-kali-linux/?expand_article=1)

### Commands

```
sudo apt update
sudo apt install curl gpg gnupg2 software-properties-common apt-transport-https
curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo install -o root -g root -m 644 microsoft.gpg /etc/apt/trusted.gpg.d/
echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" | sudo tee /etc/apt/sources.list.d/vscode.list

sudo apt update && sudo apt install code
```
