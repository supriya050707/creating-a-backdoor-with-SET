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

<img width="1920" height="1055" alt="VirtualBox_kali linux_25_09_2025_08_46_54" src="https://github.com/user-attachments/assets/339508fd-5c8f-4e31-840a-78c9aa5353dc" />


Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

<img width="1920" height="315" alt="image" src="https://github.com/user-attachments/assets/d55a35ac-7713-455a-8b58-195d34339ea0" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1920" height="324" alt="image" src="https://github.com/user-attachments/assets/cd08e568-a3d3-4539-b05b-79f06ca843b5" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT


<img width="1920" height="257" alt="image" src="https://github.com/user-attachments/assets/7cf114d6-b907-4326-a0b3-cddec0852c0b" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1920" height="312" alt="image" src="https://github.com/user-attachments/assets/1036037b-51ce-4259-b962-3ca86b67206d" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="1920" height="587" alt="image" src="https://github.com/user-attachments/assets/37af2e54-b541-46a0-a65d-37fd6031c2e8" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="1920" height="237" alt="image" src="https://github.com/user-attachments/assets/8e1bb45f-89b0-4b63-858f-b09bdb2db06c" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1920" height="1055" alt="VirtualBox_kali linux_25_09_2025_09_28_15" src="https://github.com/user-attachments/assets/ed215c2e-695b-41c4-b24f-d2e0e189c036" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1920" height="1055" alt="VirtualBox_kali linux_25_09_2025_09_28_26" src="https://github.com/user-attachments/assets/4debdf4b-79b0-466c-b10f-ba62f96bd6a2" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT
<img width="1285" height="435" alt="image" src="https://github.com/user-attachments/assets/220d0d09-9d20-4aee-981f-7c6eac8156bc" />













## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
