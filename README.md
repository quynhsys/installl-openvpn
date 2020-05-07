## openvpn-install
Secure OpenVPN installer for Debian, Ubuntu, CentOS and Arch Linux.

This script will let you setup your own secure VPN server in just a few minutes.

Here is a preview of the installer :

![](https://lut.im/IzjFrfhM18/DY8KD91W0uMhEgLp.png)
![](https://lut.im/eODTn8Sa9y/euCqh0wzXwlz3UNs.png)

## Usage

**You have to enable the TUN module otherwise OpenVPN won't work.** Ask your host if you don't know how to do it. If the TUN module is not enabled, the script will warn you and exit.

First, get the script and make it executable :

```
wget https://raw.githubusercontent.com/Angristan/OpenVPN-install/master/openvpn-install.sh
chmod +x openvpn-install.sh
```
Then run it :

`./openvpn-install.sh`

The first time you run it, you'll have to follow the assistant and answer a few questions to setup your VPN server.

When OpenVPN is installed, you can run the script again, and you will get the choice to :

- Add a client
- Remove a client
- Uninstall OpenVPN

![](https://lut.im/Z8xfJ8WqyO/3JoPmJK8VRp6zwOE)


The script is made to work on these OS :
- Debian 7
- Debian 8
- Ubuntu 12.04 LTS
- Ubuntu 14.04 LTS
- Ubuntu 16.04 LTS
- Ubuntu 16.10
- CentOS 6
- CentOS 7
- Arch Linux
