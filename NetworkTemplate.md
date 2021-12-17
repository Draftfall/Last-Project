Network Analysis

Time Thieves

You must inspect your traffic capture to answer the following questions:
![image](https://user-images.githubusercontent.com/85657022/146567857-98e53a01-1d56-4571-9022-acdaac4303eb.png)
 
⦁	What is the domain name of the users' custom site?
Frank-n-ted.com 

⦁	What is the IP address of the Domain Controller (DC) of the AD network?
 10.6.12.12
 
⦁	What is the name of the malware downloaded to the 10.6.12.203 machine? Once you have found the file, export it to your Kali machine's desktop.
june11.dll

![image](https://user-images.githubusercontent.com/85657022/146567941-b9a78a05-e748-439f-8139-ce08ccd5335f.png)





 ![image](https://user-images.githubusercontent.com/85657022/146567961-09029235-b959-46e7-9a3b-c3c3a69d4b76.png)


 


⦁	Upload the file to ⦁	VirusTotal.com. What kind of malware is this classified as?
Trojan.

![image](https://user-images.githubusercontent.com/85657022/146568010-2c36d373-cf23-4f74-bb84-ee76b049c631.png)

 
 








Vulnerable Windows Machines

The Security team received reports of an infected Windows host on the network. They know the following:

⦁	Machines in the network live in the range 172.16.4.0/24.

⦁	The domain mind-hammer.net is associated with the infected computer.

⦁	The DC for this network lives at 172.16.4.4 and is named Mind-Hammer-DC.

⦁	The network has standard gateway and broadcast addresses.

Inspect your traffic to answer the following questions:

![image](https://user-images.githubusercontent.com/85657022/146568098-17bc1448-d0e6-4298-a908-8ce7960b062b.png)

 
⦁	Find the following information about the infected Windows machine:

⦁	Host name: ROTTERDAM-PC

⦁	IP address: 172.16.4.205

⦁	MAC address: 00:59:07:b0:63:a4












⦁	What is the username of the Windows user whose computer is infected?
 matthijs.devries
 
![image](https://user-images.githubusercontent.com/85657022/146569179-cec415fa-7a89-411b-973d-6e4535183010.png)











⦁	What are the IP addresses used in the actual infection traffic?

Source: 10.6.12.203

Destination: 205.185.125.104
 
![image](https://user-images.githubusercontent.com/85657022/146568186-ef480694-9a60-4e80-8967-aac950638ed6.png)








Illegal Downloads

IT was informed that some users are torrenting on the network. The Security team does not forbid the use of torrents for legitimate purposes, such as downloading operating systems. However, they have a strict policy against copyright infringement.
IT shared the following about the torrent activity:

⦁	The machines using torrents live in the range 10.0.0.0/24 and are clients of an AD domain.

⦁	The DC of this domain lives at 10.0.0.2 and is named DogOfTheYear-DC.

⦁	The DC is associated with the domain dogoftheyear.net.




















Your task is to isolate torrent traffic and answer the following questions:

 ![image](https://user-images.githubusercontent.com/85657022/146568240-74cf52fe-10b1-4e5a-ac75-6b298074fc73.png)

 ![image](https://user-images.githubusercontent.com/85657022/146568300-ac18790f-cd49-4cb6-8089-a02d6167ecc2.png)

 ![image](https://user-images.githubusercontent.com/85657022/146568328-0ef7a86b-cbc7-4427-a47f-0ef8e82954dc.png)


⦁	Find the following information about the machine with IP address 10.0.0.201:

⦁	MAC address: 00:16:17:18:66:c8

⦁	Windows username: elmer.blanco

⦁	OS version/hostname: BLANCO-DESKTOP


⦁	Which torrent file did the user download?
User looks to have accessed several torrents:
⦁	ipod.jpg

⦁	googlevid.jpg

⦁	bettybooprythmonthereservationgrab.jpg

⦁	divxi.jpg

⦁	nshowmovie.html
