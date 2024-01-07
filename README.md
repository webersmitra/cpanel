# cPanel
***cPanel installer by WebersMitra Solution Pvt Ltd***
This Bash script automates the installation process for cPanel on various supported operating systems. cPanel is a widely used web hosting control panel that simplifies website and server management through its intuitive interface.

# Minimum Requirements
To successfully install and run cPanel, ensure that your system meets the following minimum requirements:

Processor: 1 GHz CPU or higher
RAM: 1 GB RAM (for minimal usage, higher recommended)
Storage: 20 GB available disk space

# **Operating System:**
CentOS 7 or later
Red Hat Enterprise Linux (RHEL) 7 or later

*Supported Operating Systems*
The cPanel installer script is compatible with the following operating systems:
CentOS 7 and later
Red Hat Enterprise Linux (RHEL) 7 and later

# What is a VPS Server?
A Virtual Private Server (VPS) is a virtualized server that mimics the functionality of a dedicated server within a shared hosting environment. It operates as an independent server despite sharing physical hardware with other VPS instances. VPS hosting offers more control, customization, and scalability than shared hosting.

## Getting a VPS/Dedicated Server from Whiscloud.com

[Whiscloud](https://whiscloud.com) offers VPS hosting/ Dedicated Server services at affordable prices. To purchase a VPS:

1. Visit [Whiscloud](https://whiscloud.com) website.
2. Browse available VPS/Dedicated Server plans and select one that suits your requirements.
3. Proceed to checkout and complete the payment process.
4. Once payment is processed, you will receive an email with Server login details.

## Connecting to your VPS/Dedicated via SSH using PuTTY

PuTTY is a popular SSH client for Windows that allows connecting to a remote server. Here's how to connect using PuTTY:

1. Download and install [PuTTY](https://www.putty.org/).
2. Open PuTTY and enter your VPS IP address in the "Host Name" field.
3. Set the port to 22 (default for SSH).
4. Choose the connection type as SSH.
5. Click "Open" to initiate the connection.
6. You will be prompted for a username (usually "root") and password provided by your VPS provider.

Note: It's recommended to change the default SSH port for security reasons.

# Installation Command

**For Installation in *Ubuntu/Deepin* Run**
```
wget -O ubuntu.sh https://raw.githubusercontent.com/webersmitra/cpanel/main/ubuntu.sh && chmod 755 ubuntu.sh && sudo ./ubuntu.sh
```

**For Installation in *Centos/AlmaLinux* Run**
```
wget -O almalinux.sh https://raw.githubusercontent.com/webersmitra/cpanel/main/almalinux.sh && chmod 755 almalinux.sh && sudo ./almalinux.sh
```

For Any Developement Regarding Queries Contact Us - sales@webersmitra.com
Visit Our Website - https://webersmitra.com
