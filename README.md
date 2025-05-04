# Basic-Device-Security
This repository contains a Cisco Packet Tracer lab designed to teach the basics of device security for network equipment such as routers and switches.
![image](https://github.com/user-attachments/assets/da78acf0-bc31-4515-b9a3-c33a59a6a0ad)
🧪 Lab Objective
Learn how to configure basic security on Cisco devices:

Change hostnames

Set up passwords

Encrypt passwords

Understand password encryption types

Save device configurations

🖥️ Topology
1 Router (R1)

1 Switch (SW1)

3 PCs (PC1, PC2, PC3)

✅ Tasks
Change the hostnames of the router and switch to R1 and SW1.

Configure an unencrypted enable password with the value CCNA.

Exit to user EXEC mode and test the password.

View the password in the running configuration.

Ensure that all current and future passwords are encrypted.

View the password in the running configuration again.

Configure a more secure enable secret password with the value Cisco.

Exit to user EXEC mode and return to privileged EXEC mode. Which password is now required?

View the passwords in the running configuration.

What encryption type is used for enable password?

What encryption type is used for enable secret?

Save the running configuration to the startup configuration.

⚙️ Requirements
Cisco Packet Tracer (recommended version: 8.x)

Basic knowledge of Cisco CLI

📂 File
Day-04-Lab--Basic-Device-Security-02.pkt – the main Packet Tracer file

🧠 Useful Cisco CLI Commands
bash
Копировать
Редактировать
hostname R1
enable password CCNA
service password-encryption
enable secret Cisco
show running-config
copy running-config startup-config
📸 Screenshot

🔐 Author
Created as part of training in CCNA / IT Support / Network Engineering (Netzwerktechnik).


