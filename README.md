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

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/3a12cefa-75e7-4e21-8d86-cba7505c6048)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/190608fd-771b-4db7-beda-2cfdf176209a)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected: 

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/ef5124ae-60e3-4e02-869c-c79e13059db4)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/39151790-76c9-45f4-b4ec-a01125f48ffb)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/094f41f5-1a4c-44e0-a2c0-40197096d47d)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/3f5c0a64-dc8b-48af-8b72-9a2c3fdc933a)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/66ed23ff-90e7-47e3-83bb-0887052696bd)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/8a1fd535-8f1f-475d-ae4c-1694f06a65ae)

SET logs the information regarding the Google credentials:

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/f70d5a68-c649-4931-b924-093b955a953c)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/22008686/creating-a-backdoor-with-SET/assets/118916413/f6bb2e51-e52c-4e7a-92e5-72da0e18a981)

## RESULT:

The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully.
