# Eutopia - CyberSecurity HomeLab

## Objective
Eutopia project aimed to design and implement a fully virtualized and scalable cybersecurity homelab that simulates real-world attack and defense scenarios, enabling hands-on practice in ethical hacking, threat detection, incident response, and malware analysis using industry-standard tools and technologies.

## 🛠️ Skills Gained by Setting Up the Lab

| 🗂️ Category                          | 🧠 Skills Learned                                                                                                     |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| 🧩 **Virtualization & Infrastructure** | - Installing and configuring **VMware Workstation Pro**<br>- Managing virtual machines (creation, snapshots, network settings)<br>- Allocating system resources (CPU, memory, disk) efficiently |
| 🌐 **Networking Basics**              | - Setting up **NAT and Host-only** networks<br>- Understanding internal/external network segmentation<br>- Basic virtual LAN simulation |
| 🐧 **Operating Systems & Admin Skills** | - Installing **Kali Linux**, **Ubuntu Server/Client**, and **Windows 10**<br>- Initial system configuration (users, updates, packages)<br>- Using the terminal for basic system management |
| 🔐 **Security Best Practices**        | - Hardening lab machines (e.g., disabling unused services)<br>- Isolating the lab network from the host machine<br>- Verifying VM image integrity before use |
| ⚙️ **Lab Design & Documentation**     | - Designing the architecture of the lab environment<br>- Documenting setup steps and objectives<br>- Creating repeatable setup processes (manually or scripted) |

## 🧰🔗 Tools Used

- [VMware Workstation Pro](https://www.vmware.com/products/workstation-pro.html)
- [Kali Linux](https://www.kali.org/)
- [Metasploitable 2](https://sourceforge.net/projects/metasploitable/)
- [Ubuntu Server](https://ubuntu.com/download/server)
- [Ubuntu Desktop](https://ubuntu.com/download/desktop)
- [Wazuh](https://wazuh.com/)
- [FLARE VM](https://github.com/mandiant/flare-vm)
- [Windows 10 ISO](https://www.microsoft.com/software-download/windows10)


## Steps


 📓  Kali Linux, Metasploitable, Ubuntu Server, Ubuntu client will all be on the same network (NAT), while FLARE VM will be isolated (Host-only).
 

1- VMware Workstation download & Configuration. I set a unique IP address range for my networks.

<img width="400" height="600" alt="VMware Workstation download" src="https://github.com/user-attachments/assets/3c29b7e1-29fa-495a-88db-1c16f1570487" />   <img width="400" height="600" alt="VMware Workstation configuration (I'll give a unique IP address)" src="https://github.com/user-attachments/assets/079da2e0-e31b-4502-8ce1-ac41e8da1294" />

2- Kali Linux VM installation and configuration. Then I ping google to see if everything is okay. ifconfig to confirm my IP address

<img width="400" height="600" alt="01 08 2025_23 40 47_REC" src="https://github.com/user-attachments/assets/01be9fc7-fd7d-4006-89c9-b137397b9109" />  <img width="400" height="600" alt="01 08 2025_23 44 46_REC" src="https://github.com/user-attachments/assets/454a0936-4b9d-4487-abf7-fb10f33c2a0f" />

3- Metaspoitable VM installation and configuration. On Kali Linux I'll ping Metatspoitable VM to see if it's up and running.

<img width="400" height="600" alt="Meta config" src="https://github.com/user-attachments/assets/e0ca8773-35b5-41e0-a8b8-cbead916cad0" />  <img width="400" height="600" alt="02 08 2025_00 14 05_REC" src="https://github.com/user-attachments/assets/07aaac4d-5df0-48d7-999b-d1f79ba1819e" />

4- Installation and setting up Ubuntu server for our Wazuh Manager as well as Ubuntu Client.

<img width="400" height="600" alt="02 08 2025_00 24 59_REC" src="https://github.com/user-attachments/assets/d729bc2b-e954-4b54-99cf-ba1f087913aa" />  <img width="400" height="600" alt="02 08 2025_00 30 22_REC" src="https://github.com/user-attachments/assets/e44602aa-505f-4f27-a479-96918a6bb4fc" />

5- Flare VM installation(win10 and tools) and configuration

<img width="400" height="600" alt="Flare VM" src="https://github.com/user-attachments/assets/5041e6ae-1c1e-4722-9c23-7ccd3d0557e9" />  <img width="400" height="600" alt="Flare VM config" src="https://github.com/user-attachments/assets/d48a987a-16cd-403f-911c-0031b6b7430f" />




Eutopia Lab is up 🚀

<img width="1697" height="1108" alt="Done" src="https://github.com/user-attachments/assets/16c0343a-27de-4158-b0bc-231490f699a8" />


# FIN !
