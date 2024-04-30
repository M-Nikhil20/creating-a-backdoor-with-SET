# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/9863d2bf-7ad9-465a-a5dc-3f5c9dbf1ed3)



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/bbc8838e-4c53-4138-878f-b20042f85a7d)



It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/3fafaf72-9a2f-4cb9-9ca1-9b5033961b35)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/7610d600-87d6-4b95-8e7d-9a398deb4051)



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/fd82c5ad-72ac-4630-9535-e691c61ee8f3)



It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/83394a25-2710-4d51-82a8-21a53293ed74)



It shows the following screen in which the option Google can be selected:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/7971a22e-82d5-4c5d-9666-7bad61997998)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/3bd03a9c-b230-4a83-9a34-d3f9260efacd)



In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/31473704-9f06-440e-8c50-fe88f39ff6e9)



SET logs the information regarding the Google credentials:

![image](https://github.com/M-Nikhil20/creating-a-backdoor-with-SET/assets/118707852/13d21cae-d4cd-4c55-8459-1c8707e6f658)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
