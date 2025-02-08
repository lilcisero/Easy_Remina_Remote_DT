# Easy_Remina_Remote_DT
Easy install and setup of remote desktop for linux 
Step 1: Install Remmina

First, you need to install Remmina on both your tower computer and your virtual machine laptop. Open a terminal on both machines and run the following commands:

sudo apt update
sudo apt install remmina remmina-plugin-rdp remmina-plugin-vnc

Step 2: Enable Remote Desktop on Your Tower Computer

On your tower computer, you need to enable remote desktop access. Open the settings and navigate to the remote desktop settings. Enable the remote desktop feature and note down the IP address of your tower computer.

Step 3: Connect Using Remmina

Open Remmina on your virtual machine laptop.

1. Click on the "+" button to create a new connection profile.

2. In the Protocol dropdown, select VNC.

3. Enter the IP address of your tower computer.

4. Enter the username and password for the remote connection.

5. Click Save and then Connect.Open Remmina on your virtual machine laptop.

6. Click on the "+" button to create a new connection profile.

7. In the Protocol dropdown, select VNC.

8. Enter the IP address of your tower computer.

9. Enter the username and password for the remote connection.

10. Click Save and then Connect.Open Remmina on your virtual machine laptop.

11. Click on the "+" button to create a new connection profile.

12. In the Protocol dropdown, select VNC.

13. Enter the IP address of your tower computer.

14. Enter the username and password for the remote connection.

15. Click Save and then Connect.

Step 4: Verify Connection

You should now see the desktop of your tower computer on your virtual machine laptop. If everything is set up correctly, you'll be able to control your tower computer remotely.

Explanation

Remmina is an open-source remote desktop client that supports various protocols, including VNC (Virtual Network Computing). By enabling remote desktop on your tower computer and using Remmina on your virtual machine laptop, you can access and control your tower computer as if you were sitting right in front of it.
