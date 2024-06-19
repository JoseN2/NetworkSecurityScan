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

I also did an Ipconfig on my Host machine.

![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/470875f0-58db-41ba-8c34-57806ba37291)

this is the Scan of the Router IP info 

![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/a7f3b5fd-b578-4239-ba8f-f3fb46e9609a)
Attempt to Guess an Unknown OS
![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/6a89ddb0-2575-4728-99d0-4c1d27797a0d)
Service Version Detection
![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/faf65c8b-50f4-40c2-8d6a-a6ceda9ec059)
![image](https://github.com/JoseN2/NetworkSecurityScan/assets/87278438/83b54d44-dd1b-40fa-b349-554627f77835)



Using this info I did the [sudo nmap -O  10.0.2.15] to figure out what operating system my machine was running.
sudo nmap -O -osscan-guess 10.0.2.0/24. When I ran the scan it successfully identified four responsive hosts within the specified subnet.10.0.2.2,10.0.2.3,10.0.2.4,10.0.2.15
