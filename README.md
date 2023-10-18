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

## OUTPUT:
![s1](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/60e77f28-4de0-4e5a-ab43-a03e5d7dd71f)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![s2](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/e4d35622-278e-4ac8-8090-a4aed98d7eef)


It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![s3](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/38a30297-260d-44c9-b9ae-ebfa80a36101)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![s4](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/4bdce41e-56f9-4ea8-8235-ed4c6b4da063)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![s5](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/7bf52775-d111-46c9-8d4d-c957b6e1f3d2)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![s6](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/1cc6b86f-3818-48ae-83bb-afa7bd6d6d5b)


It shows the following screen in which the option Google can be selected:

## OUTPUT:
![s7](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/016707d3-2ff6-4491-b55a-ddf7fba68457)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![s8](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/59f55872-9814-435e-97ee-b5259ebeb2b2)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![s9](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/5998d4b3-ebf1-4b28-b453-4f5eb4def334)


SET logs the information regarding the Google credentials:

## OUTPUT:
![s10](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/d8bb3bb6-5b3c-481c-9e2e-0cbcdebe6a4a)


SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![s11](https://github.com/anto-richard/creating-a-backdoor-with-SET/assets/93427534/ba312522-db72-4745-b658-7b687c14fcbd)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
