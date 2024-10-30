### Date:
# Ex-7: Creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

## AIM:
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
The command sudo setoolkit in the prompt gives menu with set prompt:</br>
![1)](https://github.com/user-attachments/assets/aeb4bb0c-8f84-4e8f-ba23-936b42de7e7e)


</br>
 It displays the following menu and select 2 for Website Attack Vectors:</br>
 
![2)](https://github.com/user-attachments/assets/0b6dc7c5-dd9e-473c-851e-e4c0948b4f05)

</br>
 The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:</br>
 
![3)](https://github.com/user-attachments/assets/219f23fe-58a4-44e3-ad98-7fa8cb212fa8)

</br>
 The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:</br>
 
 ![4)](https://github.com/user-attachments/assets/e69d2fa2-c635-4701-aec8-c66eb674c8df)

 
</br>
 It shows the following screen in which the ip address of the attacker need to be given which is the default value:</br>

 ![5)](https://github.com/user-attachments/assets/3b808de9-e0b3-4bdf-b20a-954d1bc035f9)


 </br>
 It shows the following screen in which the option Google can be selected:
</br>

![6)](https://github.com/user-attachments/assets/9b837353-446f-4c2d-9137-e545c76ad424)


</br>
 SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:</br>

![7)](https://github.com/user-attachments/assets/5185f477-a45a-4962-90d5-96168d6308e7)

 
</br>
 In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password </br>

 
![8)](https://github.com/user-attachments/assets/cddfa7da-936d-4f32-9a69-1756fff8f783)


 </br>
 SET logs the information regarding the Google credentials:
</br>

![8 1](https://github.com/user-attachments/assets/dc237c4d-2343-4cfb-a8c3-155c7155a676)


</br>
 
 SET logs the information in the xml file under /root/.set directory:
 </br>

 
![9)](https://github.com/user-attachments/assets/79d7b1f2-5f79-4b24-83c0-7cd9e81a7642)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
