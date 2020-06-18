# First Script for Kali Linux Windows App

After Enabling WSL and Installing Kali Linux App from the Microsoft Store in Windows 10, Run This Script.

## How To Use ? :

Open Kali Linux App and Run..

```sudo apt-get update```

```sudo apt-get install git```

```git clone https://github.com/thehackingsage/Kali-WSL```

```cd Kali-WSL```

```chmod +x install.sh```

```./install.sh```

:pushpin: This Installation Process Will Take Some Time.

Download and install VcXsrv X Server on Windows : [vcxsrv v1.19.6.0.exe](https://sourceforge.net/projects/vcxsrv/files/vcxsrv/1.19.6.0/)

:pushpin: Don’t Use Any Other Version.

After That, Start VcXsrv, Accept Change in Firewall Rules Then Exit VcXsrv..

## How To Start GUI Mode? :

as normal user : ```~/startx```

as root : ```sudo /root/startx```

#### or you can also start GUI Mode by typing : ```startx```

You can also Run Kali Desktop in a RDP Session 

In Kali WSL, type : ```sudo /etc/init.d/xrdp start```

then open run, type mstsc.exe and connect to ```127.0.0.1:3390```

## How To Start Hacktronian? :

after installation you can execute tool by typing ```hacktronian```

That's It... If You Like This Repo. Please Share This With Your Friends..

& Don't Forget To Follow Me At [Twitter](https://www.twitter.com/thehackingsage), [Instagram](https://www.instagram.com/thehackingsage), [Github](https://www.github.com/thehackingsage) & SUBSCRIBE My [YouTube](https://www.youtube.com/channel/UCYK1n9A4TUq1CvGc6F3DzoA) Channel..!!!

HAPPY HACKING !!! 
