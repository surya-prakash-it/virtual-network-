Project Name:Virtual Network Simulation Description

Team Name:Tech Meeters

Team Leader:Parameshwar N.S
Team member:Sathya Seelan M
            Suriya Prakesh A


Virtual Network Simulation Description:
STEP1: Download the virtual Box in your Host OS and Install the 
Guest OS in the virtual machine
 Virtual Box: Download virtual box from official website
 
 STEP2: First we will share a folder from host machine to one VM. 
Create a folder in the Host Machine.

 STEP3:Install the VM and download the necessary files and then 
install another VM say vm2 and download the necessary files.

 STEP4:Now run the VM and Go to Device->Insert Guest additional 
CD image option and install the CD image and eject the CD image 
this helps in the access of file from one and eject the CD image this 
helps in the access of file from one VM to another.

 STEP5:Go to Device->Shared Folder->Shared Folder Settings and a 
dialog box appears.

 STEP6: Click on the Add File as marked in the above picture and 
give the directory of a share folder in the Host Machine and click ok.

 STEP7: Now open the terminal and create a folder of your choice 
and command sudomkdir ~/Desktop/ windowshare in the vm 
folder with windowsshare will be created in the vm desktop.And 
type sudomount -t vboxf “folder name” ~/Desktop/ windowshare 
and enter.

STEP8:Now, we can access the shared file in the VM. Now to 
share folder from one VM another VM.

STEP9: Create a file inside the folder windows share of VM and 
Run the VM2 and do step 4 to 6.

STEP10:Now open the terminal in vm2 and create a folder of 
your choice as step 7.

STEP11:Now type sudo munt -t vboxsf “filename” 
~/Desktop/”folderinvm2”

 STEP12:Now enter and view the folder and the folder 
in the VM1 will be seen in VM2
