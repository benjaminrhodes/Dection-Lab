# Windows Virtual Machine Set up

## Objective
The goal of setting up a Windows Virtual Machine (VM) for our cybersecurity project is to create a safe and controlled environment where we can test and analyze potential security threats. This setup allows our team to simulate attacks and develop strong defense strategies without risking the main network.


### Skills Learned


- Virtualization setup process 
- Resource Allocation: Learn how to give the right amount of CPU, memory, and storage to the VM.
- Development of critical thinking and problem-solving skills in cybersecurity.
- Familiarization with Windows.

### Tools Used
[Bullet Points - Remove this afterwards]

- Virtual Box
- Internet
  

## Steps

## Step 1. Downlaod Virtual box
Go to virtualbox.org and download the software for the Host OS you have Windows or macOS
![image](https://github.com/user-attachments/assets/c7085bcf-01b5-490b-b8f7-61b66d0629e2)
<br>
## Step 2. Setup Virtual Box 
Set up virtual Box on your machine be sure to put in the correct file path or chose the desktop.
![image](https://github.com/user-attachments/assets/8d04dc5b-bc8a-4ca2-bb7b-3332e52f07a6)
<br>

## Step 3. Downlaod the Windows ISO
Go to https://www.microsoft.com/en-us/evalcenter/evaluate-windows-11-enterprise and download the ISO for Windows 11. It's worth to note that this is an evaluation version so there might be some features you loose in 90 days. However, it is good for practicing on a windows computer in a lab setting.
<br>
![image](https://github.com/user-attachments/assets/ce4755b9-133a-4a4b-b1e1-61dda73a8455)
<br>
*Ref 1: They will ask you for your information before you download it and the download will take sometime so feel free to take a quick break for coffee!*
<br>

## Step 4. Configure the Virtual Machine in Virtual Box
Open Virtual Box and click on the Star that says "New" and add in the Name, The ISO file, and click the checkbox for skip unattended installation so you can see what the actual installation process looks like. 
![image](https://github.com/user-attachments/assets/9ca76c32-c780-4ee6-8239-0b32bf2e070a)
<br>
## Step 5. Configure the Hardware settings
Now we will be deciding how much resources we will be allocating to this VM. This includes Base memory and Processors. By default it sets it to 4 giabytes of memory and 2 processors. If you have the resources to upgrade that to 8 gigabytes and 4 processors I would recommend it.
<br>
![image](https://github.com/user-attachments/assets/b937fdec-c59d-45fe-971a-835420cd366e)
<br>

## Step 6. Configuring the virtual hard disk
For the virtual hard disk we are going to leave it as the default. 
![image](https://github.com/user-attachments/assets/f9489337-fcaf-456a-abff-132d29f9d5d6)
<br>

## Step 7. Settings Summary
Review the settings for your new Virtual machine and click finish.
![image](https://github.com/user-attachments/assets/d8be798d-f69b-4f43-b6fe-ee4365b3be8d)
<br>

## Step 8. Start your new Windows 11 VM
Click on the VM you just made and click the green arrow to start!
![image](https://github.com/user-attachments/assets/c869a732-0709-4d14-a87a-d8aa66977fa6)
<br>

## Step 9. Go through the setup process for Windows
After you click start, a box will pop up and ask you to press any key.
![image](https://github.com/user-attachments/assets/e0ba718a-4d11-499c-9a88-09f915546ac3)
<br>
Choose your language, timeformat, and kayboard input. 
<br>
![image](https://github.com/user-attachments/assets/806c5cc5-7fba-4989-9f4b-386ea6f17a5a)
<br>
Click Install now.
<br>

## Step 10. Agree to the Software license
Click on the checkbox to aggree to the license and hit next.
![image](https://github.com/user-attachments/assets/9043cb65-641d-4ff9-bea0-a1f2f86aee06)
<br>

## Step 11. Software installation
Click on the custom install and use the default drive. Click next to continue.
![image](https://github.com/user-attachments/assets/b6a56cbb-daeb-484f-b16a-e38cb9d3ae36)
<br>
*Note: After this, it will run through and restart a few times. Feel free to take a quick break!
<br>

## Step 12. Choose the region or country for you
Pick what region or country you want your windows VM to be based off of.
![image](https://github.com/user-attachments/assets/3f12469b-5f09-4e02-9510-248892646b18)
<br>

## Step 13. Choose the right keyboard layout/input
Choose the keyboard layout you want and add additional keyboards if needed.
![image](https://github.com/user-attachments/assets/a97dd880-1223-48cd-8835-3a3def9defb8)
<br>

This is where you would add your second keyboard layout.
![image](https://github.com/user-attachments/assets/404ce17e-0153-4f6b-9321-ec201a9af2d9)
<br>

## Step 14. Setting up your account
Once you have reached this point you can login with your microsoft credentials (username and password) or you can click "Sign-in options". I'm going to click "Sign-in options" and select "Domanin join instead".
![image](https://github.com/user-attachments/assets/059307c6-f8a9-4e21-a487-41926e6c1787)
![image](https://github.com/user-attachments/assets/0ea19202-63d0-4512-b2b9-cb8e88d4fb19)
<br>

## Step 15. Input user information

In this section you are going to input your name, password, and 3 security questions.
![image](https://github.com/user-attachments/assets/21325297-9172-4a00-9aac-d345e141cfdd)
<br>
Please note to select no on all of the sliders if you want microsoft to collect less information from you.
<br>
![image](https://github.com/user-attachments/assets/99156b9a-3f0f-4c9d-a181-dc518b1b940f)
After that just click accept and it might take a few minutes to finish setting up your install.
<br>

## Step 16. Log in!
Log into your new account with the credentials you just made and Enjoy Windows 11!
![image](https://github.com/user-attachments/assets/49886fce-81c5-4488-9a7a-f5c9b8f192a8)

