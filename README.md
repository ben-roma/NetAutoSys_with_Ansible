
# NetAutoSys with Ansible

## 🌐 About The Project
This repository contains the implementation of automated DMVPN (Dynamic Multipoint Virtual Private Network) deployment using Ansible. Developed as part of a Master's thesis at Kigali Independent University, this project aims to simplify network management across multi-vendor environments, enhancing efficiency and reducing errors through automation.

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
  ```
- **GNS3**
  - [Follow the official GNS3 installation guide](https://docs.gns3.com/docs/getting-started/installation/)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ben-roma/NetAutoSys_with_Ansible.git
   ```
2. Navigate to the project directory
   ```sh
   cd NetAutoSys_with_Ansible
   ```
3. Edit the inventory files to include your network devices' IPs and credentials.

4. Run the Ansible playbook to set up the network.
   ```sh
   ansible-playbook setup-network.yml
   ```

## 📚 Usage

Use this automation setup to deploy DMVPN configurations across your network devices efficiently. Modify the Ansible playbooks as needed to fit your specific network requirements.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📩 Contact

Ben Roma

Project Link: [https://github.com/ben-roma/NetAutoSys_with_Ansible](https://github.com/ben-roma/NetAutoSys_with_Ansible)

## 📖 Acknowledgements

- [Ansible Documentation](https://docs.ansible.com/)
- [GNS3 Community](https://www.gns3.com/community)
- [Kigali Independent University](http://ulk.ac.rw/)
- [ALX Africa](https://www.alxafrica.com/)
