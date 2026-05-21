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
## OUTPUT

<img width="649" height="953" alt="image" src="https://github.com/user-attachments/assets/f30f0a9e-73e7-427a-aae5-35e68878eab2" />

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="430" height="355" alt="image" src="https://github.com/user-attachments/assets/8749def6-40b0-401b-a3f9-fe18549b379a" />

It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="943" height="311" alt="image" src="https://github.com/user-attachments/assets/75014341-1d04-4a29-897f-bf3b1e8fd26b" />

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="694" height="370" alt="image" src="https://github.com/user-attachments/assets/fad094e6-29fe-4790-9f9b-33f62c1e5303" />

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="876" height="477" alt="image" src="https://github.com/user-attachments/assets/fc266dae-a99c-4de2-9244-1092ae482346" />

It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="932" height="649" alt="image" src="https://github.com/user-attachments/assets/61e8812e-30dd-4df2-ac07-2f9b5cae3c1a" />

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="907" height="1190" alt="image" src="https://github.com/user-attachments/assets/4c471e18-7a32-4fee-905a-9b16bf111143" />

In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="931" height="245" alt="image" src="https://github.com/user-attachments/assets/c6f5b1f0-227d-41e5-9f91-8b81d62ac655" />

SET logs the information regarding the Google credentials:
## OUTPUT

<img width="929" height="390" alt="image" src="https://github.com/user-attachments/assets/fba8b42d-7c51-479d-bd4d-f166c96459b4" />

SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="641" height="478" alt="image" src="https://github.com/user-attachments/assets/63b12027-3bc0-4421-ac35-985312d3bd31" />

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
