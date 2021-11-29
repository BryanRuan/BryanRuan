# Review Questions - Chapter 12

1) Using the ip2 suite of tools, which command(s) would show your IP address?

  
   c. `ip address show`
   d. `ip a sh`

2) Using the ip2 suite of tools, which command would show your routing table?

   a. `ss`
   b. `route`
   c. `ip route show`
   d. `ip -r`

3) What tool could you use to establish if a server is responding to requests?

   
   b. `ping`
  

4) What is the purpose of a netmask?



5) What is the purpose of DNS?



6) What is the name of the systemd firewall?

   a. systemd-firewalld
   b. systemd-firewall
   c. firewalld-cmd
   d. ufw

7) What would be the command to list all of the firewalld public zone ports in use?

   a. `sudo systemctl status firewalld`
   b. `sudo firewalld-cmd --zone=public --list-all`
   c. `sudo firewall-cmd --zone=public --list-all`
   d. `sudo firewall-cmd --list-all`

8) If you had a CIDR block of /24 and a network address of 192.168.1.0, how many IP addresses would you have?

  
   d. 256

9) What is the default port for HTTPS (TLS/SSL)?

   a. 80
   b. 3000
   c. 8080
   d. 443

10) Using Network Manager, what tool is used to release a DHCP address from the command line?


    c. `dhclient -r`


11) Using the ip2 suite, what command can be used to monitor and examine all current local ports and TCP/IP connections?

    a.  `ss`
  

12) Where are your network card settings located on Ubuntu while using Network Manager?

/etc/network/interfaces

13) Where are your network card settings located on Fedora using Network Manager?

/etc/sysconfig/network-scripts

14) Where are your network card settings located on Ubuntu using Netplan?

 /etc/netplan/config.yaml

15) What are the two major opensource webservers?

    a. Apache, Nginx
 

16) What are two related and major opensource relational databases?


    b. MariaDB and MySQL


17) What command would you type to get to the MySQL command line prompt as the root user?

18) What is the file location that the system uses as a *local DNS* for resolving IP?


    b. `/etc/hosts`
 
19) What flag would you add to this command to make it survive a reboot: `sudo firewall-cmd --zone=public --add-port=22/tcp`

    a. `--peppermint`
    b. `--permenant`
    c. `--allow`
    d. `--list-all`

20) Before systemd, NIC interface naming schemes depended on a driver based enumeration process. They switched to a predictable network interface naming process that depends on what for the interface names?

   
    b. interface names depend on physical location of hardware (bus enumeration)

