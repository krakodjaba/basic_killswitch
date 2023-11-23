UFW VPN Killswitch Setup

Author: github.com/krakodjaba
Telegram: t.me/telanalysis
Description

This script is designed to quickly set up the Uncomplicated Firewall (UFW) with a killswitch feature in conjunction with VPN. The killswitch ensures traffic blocking if the VPN connection is lost, enhancing the security of your network.
Installation and Usage Instructions

    Install UFW:

    bash

sudo apt install ufw -y

Download the script:

bash

wget https://raw.githubusercontent.com/krakodjaba/ufw-vpn-killswitch/master/ufw_vpn_killswitch.sh

Make the script executable:

bash

chmod +x ufw_vpn_killswitch.sh

Run the script as a superuser:

bash

    sudo ./ufw_vpn_killswitch.sh

Using the Script

The script provides an interactive setup experience for UFW with the specified VPN parameters. The user inputs the IP for legitimate connection, the number of network interfaces to configure, as well as the names of interfaces and the VPN. After configuration, the script activates UFW and displays a success message.

Note: The script automatically installs UFW if it is not installed and confirms the package installation without user confirmation.
Important

    Authorship: github.com/krakodjaba
    Telegram: t.me/telanalysis

    License: This project is distributed under the MIT License.
