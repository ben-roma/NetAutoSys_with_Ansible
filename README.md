# NetAutoSys with Ansible

## 🌐 About The Project
This repository contains the implementation of automated DMVPN (Dynamic Multipoint Virtual Private Network) deployment using Ansible. Developed as part of a Master's thesis at Kigali Independent University, this project aims to simplify network management across multi-vendor environments, enhancing efficiency and reducing error through automation.

### 🛠 Built With
- **Ansible**: Used for automating network configuration and management tasks.
- **GNS3**: Employed for creating a realistic network simulation environment.
- **Ubuntu**: Operating system of choice for hosting the Ansible controller.

## 🚀 Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- **Ansible**
  ```sh
  sudo apt update
  sudo apt install ansible
GNS3
Follow the official GNS3 installation guide
Installation
Clone the repo

sh
Copier le code
git clone https://github.com/ben-roma/NetAutoSys_with_Ansible.git
Navigate to the project directory

sh
Copier le code
cd NetAutoSys_with_Ansible
Edit the inventory files to include your network devices' IPs and credentials.

Run the Ansible playbook to set up the network.

sh
Copier le code
ansible-playbook setup-network.yml
📚 Usage
Use this automation setup to deploy DMVPN configurations across your network devices efficiently. Modify the Ansible playbooks as needed to fit your specific network requirements.

📄 License
Distributed under the MIT License. See LICENSE for more information.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
📩 Contact
Ben Obame
Project Link: https://github.com/ben-roma/NetAutoSys_with_Ansible

📖 Acknowledgements
Ansible Documentation
GNS3 Community
Kigali Independent University
ALX Africa