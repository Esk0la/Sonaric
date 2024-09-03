# Sonaric
![image](https://github.com/user-attachments/assets/8491bf3b-5873-4a09-a6b6-93c334a0b99a)

Minimum System Requirements
4 GB RAM - 2 CPU cores - 20 GB free disk space - 64-bit operating system

https://tracker.sonaric.xyz/

https://x.com/Sonaricnetwork

https://discord.gg/MZ247hw47z

Update
```
sudo apt update && \
sudo apt install curl git jq build-essential gcc unzip wget lz4 -y
```
Upload the required file and grant permissions
```
wget https://raw.githubusercontent.com/aksamlan/Sonaric/main/sonaric.sh && chmod +x sonaric.sh && ./sonaric.sh
```
Check if your node has been successfully installed
```
sonaric node-info
```
Run the GUI
replace user@your-vps-ip" with your own IP (for example: root@123.456.789)
```
ssh -L 127.0.0.1:44003:127.0.0.1:44003 -L 127.0.0.1:44004:127.0.0.1:44004 -L 127.0.0.1:44005:127.0.0.1:44005 -L 127.0.0.1:44006:127.0.0.1:44006 user@your-vps-ip
```
Once you enter it, enter your server password and it works.

Enter this code to see your points on the server
```
sonaric points
```
 To change name
```
sonaric node-rename
```
‼️Save mysonaric.identity in a safe place. It is located in the root folder.
