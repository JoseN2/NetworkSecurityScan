<h1>NetworkSecurityScan</h1>

<h2>Description:</h2>
Home Network Security Scanner: A learning project in vulnerability identification and mitigation using Nmap and Nessus. This project demonstrates basic network scanning techniques and highlights the importance of secure home network configurations

<h2>Learning Objectives:</h2>
Gain practical experience with Kali Linux and network security tools.
Understand the functionality of network scanners like Nmap.
Learn to identify devices and services running on a network.
Recognize the importance of keeping software updated to address vulnerabilities.


<h2>Environments and everyting else Used </h2>
- <b>Windows 10</b> 
- <b>Oracle VM VirtualBox</b> 
- <b>Kali Linux </b> 

<h2>Program walk-through:</h2>

![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/1dda1a46-ec1c-4393-bf74-a5e0fd87e011)

Using the terminal I went into the desktop directory. There I created a new directory called NetworkProject. The first thing I did was use the ifconfig command and store it in a Txt file to figure out what my subnet was. 


![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/0f841c66-749c-4152-bc95-148c1b03d544)

I opened it and saw that it was Iner 10.0.2.15.

![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/e873f103-ad5c-4a1b-a2c6-47a267edbfdc)

I also did a Ipconfig on my Host machine.








Using this info I did the [sudo nmap -O  10.0.2.15] to figure out what operating system my machine was running.
