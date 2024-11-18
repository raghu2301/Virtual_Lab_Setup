# Virtual_Lab_Setup
## Overview
Setting up a lab for cybersecurity involves creating an isolated and controlled environment where you can test, learn, and experiment with tools, techniques, and systems without risking harm to production networks or systems. Here’s a step-by-step guide:

**Choose Your Lab Setup**

You can set up a lab using:
- **Physical Hardware:**
   - Use old computers, switches, routers, and servers for a dedicated lab.
   - Benefit: Provides a hands-on experience similar to real-world setups.

- **Virtual Environment:**
   - Use virtualization software like VMware, VirtualBox, or Hyper-V to create virtual machines (VMs).
   - Benefit: Flexible, cost-effective, and easy to reset.

 - **Cloud Platforms:**
   - Use cloud services like AWS, Azure, or Google Cloud.
   - Benefit: Scalable and accessible from anywhere.

Here we will be learning about how to setup a **Virtual Environment**

Following software needs to be downloaded to setup a Virtual Environment:
- **Virtualization Software:** VirtualBox, VMware Workstation
- **Operating Systems:** Linux (e.g., Kali Linux, Ubuntu), Windows (e.g., Windows 10, Windows 11)

Steps to download these software are as follows:

Virtualization Software:
To Download VirtualBox:
   1. Goto https://www.virtualbox.org/wiki/Downloads
   2. Select the VirtualBox Platform Packages you want to download:
   3. And also download the Virtualbox Extension Pack.
      
![image](https://github.com/user-attachments/assets/0c2c79ae-a045-431e-9bd1-7c4f0e8eec31)

Operating Systems:
To Download Kali linux:
  1. Goto https://www.kali.org/
  2. Click on download option.
  3. Select virtualmachine.
     
![image](https://github.com/user-attachments/assets/dac8faf6-dbb5-4fd9-a507-9f2e553aebe1)

 4. Download the setup file for VirtualBox.
    
![image](https://github.com/user-attachments/assets/fa2d2145-87cc-4702-827a-0557647b4546)

 To Dowbload Ubuntu:
  1. Goto https://ubuntu.com/
  2. Select Ubuntu Desktop from Products dropdown menu
     
![image](https://github.com/user-attachments/assets/b8233ae5-e0cf-4671-9b68-8a0c5f051f54)

 3. Click on download option
    
![image](https://github.com/user-attachments/assets/bd157133-994f-4151-926e-53831f995e5b)

We got all the software needed to setup a **Virtual Environment**

Now its time for **Installation** Process:
 1.	Install the VirtualBox.
 2.	Install the extension pack for VirtualBox.

After installing VirtualBox:
 1. Open VirtualBox.
 2. Click on New Button.
    
![image](https://github.com/user-attachments/assets/57551c65-1d04-46ee-ac02-190b3f548c9c)

 3. A pop up window will appear
    ![image](https://github.com/user-attachments/assets/af8393fc-2a64-4056-9c83-1d195d6fa2a9)

 Fill the name section.
 Select the Folder you want to install your Ubuntu OS.
 Select the path of your **Ubuntu Iso** file.
 Either check **skip unattended installation** or goto **unattended install** tab.

 ![image](https://github.com/user-attachments/assets/1a52049b-49dd-4812-a861-e557346beb33)

 Set your **Username** and **Password**

  4. Click on "Finish" button.

Your Operating System will be added on your VirtualBox.

![image](https://github.com/user-attachments/assets/744f19f6-345f-4568-a58b-bc91e4967b0a)


 5. Now select the Operating System you just created and click on **settings**

A popup window will appear


![image](https://github.com/user-attachments/assets/009f5f83-c23e-4f1a-a81d-dfa4972e12fc)

 6. Go to **Advanced** option in **General** tab.
Select **Bidirectional** from drop down menu for **Shared Clipboard** and **Drag ‘n’ Drop** if you want to copy/ paste anything VirtualBox OS to your PC.

 7. Goto **System** tab and assign **base memory** you want to give to your Virtual Operating System.

![image](https://github.com/user-attachments/assets/c80f9320-6381-43a5-bf34-93ef5aa5d089)

 8. Goto **Network** tab and select **Bridged Adapter** in **Network Adapter** from drop down menu.

![image](https://github.com/user-attachments/assets/f92058a8-ec12-4c12-b72b-57f208fa81b1)


 9. Click **OK**
You are all set for Oprating System Installation.

 10. Click on **Start** Button

Your Ubuntu installation will start.


Steps to insatll kali linux:
 1. Extract the Kali linux downloaded file.
 2. Open the extracted folder.
 3. Click on **Virtual disk image** file.
    
![image](https://github.com/user-attachments/assets/ba8aa139-9722-463f-86bf-77720f347116)

 4. Kali linux will be added to your VirtualBox.
 5. Now follow the step 5 to step 10 which is mention above.

# Conclusion
Your Virtual lab is ready with Ubuntu and Kali linux.




















