# printing-CentOS

Lab 
Type the command you used unless asked to provide a screenshot capturing the result of the command

Lab 30.1 Using Probing Tools
STEP 1. Open a window.

STEP 2. Switch to the root account.
sudo su -

STEP 3. Execute the nmap command to probe for open TCP on the local system.
     nmap -p 1-65535 localhost 

STEP 4. Execute the nmap command to probe for open UDP on the local system.
nmap -sU -p 1-65535 localhost 

STEP 5. Execute the nmap command to probe for ports 5000–10000 on the local system.
nmap -p 5000-10000 localhost 

STEP 6. Execute the netstat command to display a summary of network packet information by protocol. <Provide a screenshot, below>


<img width="266" alt="image" src="https://github.com/vladdyvlad/printing-CentOS/assets/89713001/22c89fe9-b140-479a-a239-50a887b05e48">

 

STEP 7. Execute the netstat command to display the routing table. <Provide a screenshot, below>

 
<img width="278" alt="image" src="https://github.com/vladdyvlad/printing-CentOS/assets/89713001/b723e4d7-618f-4d90-92ef-d28008a7a4ad">




STEP 8. Execute the netstat command to display all listening sockets. . <Provide a screenshot, below>

<img width="204" alt="image" src="https://github.com/vladdyvlad/printing-CentOS/assets/89713001/a3fa9f7c-2932-4997-9fb6-6946e02d7fc0">



STEP 9. Execute the lsof command to open network sockets.
lsof -i 

STEP 10. Execute the lsof command to open network sockets without resolving hostnames or port names.
lsof -ni

