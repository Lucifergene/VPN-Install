# PritUNL-Installation-Ubuntu
Installing PritUNL VPN in Ubuntu Machine

# Installation
- Launch VM in the region where you want to fake.
- Open all ports of the VM
- Open the terminal and type the following:

`sh -c "$(wget https://raw.githubusercontent.com/Lucifergene/PritUNL-Installation-Ubuntu/main/pritunl.sh -O -)"`

## Minimum Hardware Requirements
- **1 GB RAM**
- Ubuntu Linux
- Standard HDD
- UDP Ports Open

## Desktop Access
- Download the PritUNL client from the link. [Download](https://github.com/pritunl/pritunl-client-electron/releases/download/1.2.2799.2/Pritunl.exe)
- Create a new user from the Web Console.
- Download the `.tar.gz` file from the Web Console.
- Import the file in the PritUNL Client.

## Mobile Access
- Download OpenVPN Client Application from PlayStore/AppStore.
- Download the `.ovpn` file from the web console. [Refer](https://docs.pritunl.com/discuss/5ae6df404bcbef000360f3ba)
- Import the file in the Mobile Application and login with the Username and Password 


## Troubleshooting
- Restart the machine if the webpage doesnot open


## Contributors

[Meghdut Mandal](https://github.com/Meghdut-Mandal)
