# UFW VPN Killswitch Setup

**Author:** [github.com/krakodjaba](https://github.com/krakodjaba)  
**Telegram:** [t.me/telanalysis](https://t.me/telanalysis)

## Description

This script is designed to quickly set up the Uncomplicated Firewall (UFW) with a killswitch feature in conjunction with VPN. The killswitch ensures traffic blocking if the VPN connection is lost, enhancing the security of your network.

## Installation and Usage Instructions

1. **Install UFW:**
   ```bash
   sudo apt install ufw -y
   ```
2. **Download Script:**
   ```
   wget https://raw.githubusercontent.com/krakodjaba/basic_killswitch/main/killswitch -O ufw_vpn_killswitch.sh
   ```
3. **Give a permissions to file:**
   ```
   chmod +x ufw_vpn_killswitch.sh
   ```
4. **Starting Script:**
   ```
   sudo ./ufw_vpn_killswitch.sh
   ```
License: This project is distributed under the MIT License.
