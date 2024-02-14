
1. Created a instance .
2. Connect instance via SSH Client .
3. Update your system (server) .
4. Install OPENVPN .
5. Give permissions to your OPENVPN .
(give executable permission)
6. Run openvpn-install.sh to install OPENVPN server .
using command
$ SUDO ./openvpn-install.sh

protocols ? UDP
port ? 1194
DNS ? Google or 1.1.1.1
Client Name ? Prince
Here file will be created with a name PRINCE.OPENVPN

7. Check status of OPENVPN .
using command
$ SUDO SYSTEMCTL STATUS ➡️ start (if inactive)

8. Share the file that created in step [6]
using command to download file to local system
SCP USERNAME@SERVER's[ipv4]:~/filename .

after then import that file to OPENVPN client ....
# Prakassh-DC
