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

## **Android hacking**

**Goal**

Hacking the android using kali linux

**Let&#39;s do it.**

For hacking a android it is not easy as we see also there is high sort of security in our android and other devices it is becoming harder to hack it but lets see how it is going to work but it is not going to be a successful one.

So lets create the payload for hacking the android device. Payload is nothing but a simple form of virus which will help us to connect to the shell of android devices.

Lets check our local host IP so that we can configure our payload.

![](https://github.com/whitedevil1710/LetsHackit/blob/main/ip.png)

From here we can find our IP is **10.0.2.15**

Now lets create a payload.

![](https://github.com/whitedevil1710/LetsHackit/blob/main/payload.png)

So we successfully created the payload

![](https://github.com/whitedevil1710/LetsHackit/blob/main/apk%20created.PNG)

Now lets send this to android and install the application there

![](https://github.com/whitedevil1710/LetsHackit/blob/main/apk.png)

As it is successfully downloaded the file successfully

![](https://github.com/whitedevil1710/LetsHackit/blob/main/app.png)

Now we can see that it is installed in the phone

Now let&#39;s open the Metasploit 

![](https://github.com/whitedevil1710/LetsHackit/blob/main/metasploit.png)

So as it is shown that the Metasploit has opened let&#39;s configure the payload and try exploiting it

![](https://github.com/whitedevil1710/LetsHackit/blob/main/exploit.png)

As it is shown the session didn&#39;t opened due to high security in mobile.
