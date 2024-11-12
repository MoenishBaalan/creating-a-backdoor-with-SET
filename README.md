![377028273-f1779572-cb0f-40ed-a1fe-2c2c4898117e](https://github.com/user-attachments/assets/68ecc155-0b43-4560-8558-719deec8b194)# creating-a-backdoor-with-SET
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
![377026627-8e3bb125-d21f-441c-937d-35c0527cfd8b](https://github.com/user-attachments/assets/904da0e0-c301-4599-9df1-cbe87e32ea8c)

### It displays the following menu and select 2 for Website Attack Vectors:
![377026890-c5c6b2dd-5d2f-465b-ad26-679adde44069](https://github.com/user-attachments/assets/30add88a-d6e5-41b7-b7d6-7bde51690985)


### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![377027061-ba03ce43-7b42-40e0-9778-c1c5c6a342e5](https://github.com/user-attachments/assets/a272fb29-db26-4987-b252-a0c91ca567f1)

### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![377027188-27e63d5b-13d5-4f20-948e-eb9358598607](https://github.com/user-attachments/assets/ed50414e-b136-486d-bcf7-ae949be1314c)

### It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![377027371-9f178493-578a-47df-9d15-feac3665fca2](https://github.com/user-attachments/assets/5283d747-7858-420a-a9fb-368423bb7230)


### It shows the following screen in which the option Google can be selected
![377027544-0f1748e3-9d60-49de-8069-24be0e225bd3](https://github.com/user-attachments/assets/0e9961d9-366a-428d-8f2b-d987356dee69)


### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![377027788-9255140d-5ed5-404e-bbdc-d561c251f3cf](https://github.com/user-attachments/assets/aae7d3d8-d715-4a8d-9276-edf77cac74a3)


### In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![377028011-889b0361-824d-4016-aa22-0f35a89eed29](https://github.com/user-attachments/assets/88ec84fc-11fe-448e-80aa-f4c4b83fbac2)


### SET logs the information regarding the Google credentials:
![377028273-f1779572-cb0f-40ed-a1fe-2c2c4898117e](https://github.com/user-attachments/assets/507f9edf-41a6-4021-9c83-396a3aaccb80)


### SET logs the information in the xml file under 
![377028273-f1779572-cb0f-40ed-a1fe-2c2c4898117e](https://github.com/user-attachments/assets/18b666c4-931d-4532-a9de-6a3e2a199b9c)
/root/.set directory:



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
