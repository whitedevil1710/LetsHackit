# **Let&#39;s Hack it**

## **Linux Hacking**

## *Goal*

We have to hack the metasploitable using the kali linux

## **Let&#39;s Do it**

**So we have to get the IP of the metasploitable. so lets see the IP of metasploitable.**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/metasploit%20ip.png)

**Now let&#39;s check the ports which all respond using nmap**

**The option -sP in Nmap tells Nmap not to do a port scan after host discovery, and only print out the available hosts that responded to the scan. This is often known as a &quot;ping scan&quot;.**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/ipscan.png)

**So now we got the IP of metasploitable we found that this IP is live now lets find open ports of this IP using nmap.**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/nmap.png)

**So we find that the 21 port is open which we are going to exploit as it is a ftp port so we are exploiting it using Metasploit.**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/msfconsole.png)

**After opening Metasploit let&#39;s configure the exploit**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/exploitation.png)

**After exploitation it connects to the shell of metasploitable. We can see the files in home directory and try creating new file named hacked through kali linux in metasploitable.**

**Lets see the folders in metasploitable**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/metasploitableinit.png)

**Now lets list the files using ls and lets make a directory.**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/connected%20session.png)

**So let&#39;s check in metasploitable weather it is created or not.**

![](https://github.com/whitedevil1710/LetsHackit/blob/main/metasploitable.png)

### **So we found that we sucessfully done with hack**
