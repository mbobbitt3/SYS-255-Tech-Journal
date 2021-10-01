# SYS-255-Tech-Journal

# LAB 01 Environment Setup
In this lab we cofnigured the firewall for LAN and WANs assigning each interface their own identifier em0 and em1 as well as changing some network configuration options on a host machine to utilize the firewall we had set up on another VM. We used some basic networking commands as well like tracert, ipconfig, whoami, etc. to verify that we had configured our firewall correctly. 

# LAB 02 DNS + ADDS Role
In this lab we configured DNS and AD roles for the WKS01 we used the windows Server Manager to configure AD roles for the windows system and then created an alias using DNS to use the firewall system that we created during the previous lab. 

# Lab 03 Linux Lab
In this lab we configured a linux box to use the DNS settings we configured in the last lab. We set an IP address and new hostname to the linux box and then went on to configure DNS settings for the linux box.

# Lab 04 DHCP
in this lab we configured the linux box for DHCP and the workstation and AD machines to now be using DHCP which was configured on the linux box. We configured the firewall to allow for dhcp connections and installed the dhcp services on the linux box as well. We also did some remote management using ssh 

# SSH Securing
We went into the /etc/ssh directory and vi the sshd_config file and add the following line to it PermitRootLogin no and :wq out of vi and then do a systemctl sshd restart to reset the ssh daemon and then we are done. 
