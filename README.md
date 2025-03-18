# 0G DA Client Auto Install

This script automatically installs and runs the 0G DA Client using Docker.

## 📌 Requirements
- A server/VPS running **Ubuntu**
- **Docker** must be installed (the script will install it if not available)

## 🚀 How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/zilong77/da-client-auto.git
   cd da-client-auto
   ```

2. **Run the Installation Script**
   ```bash
   chmod +x install.sh
   ./install.sh
   ```

3. **Enter Your Private Key**
   - When prompted, enter your **private key**.
   - The input will be hidden for security.

4. **Verify Node is Running**
   ```bash
   docker ps
   ```
   Ensure the `0g-da-client` container is running.

5. **Check Node Logs**
   ```bash
   docker logs 0g-da-client -fn 100
   ```

## 🔧 Additional Commands

- **Stop Node**
  ```bash
  docker stop 0g-da-client
  ```

- **Remove Node**
  ```bash
  docker rm 0g-da-client
  ```

- **Restart Node**
  ```bash
  docker start 0g-da-client
  ```

---

💡 **This script automates the installation and configuration of the 0G DA Client node, making the process easier and faster!**
