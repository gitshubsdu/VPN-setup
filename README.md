VPN setup through Virtual Box
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- This is my lab for setting up a VPN on Virtual Box

Process
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Installing Virtual Box (oracle)

Went to https://www.oracle.com/virtualization/virtualbox/
- Downloaded Oracle Virtual Box
<img width="2376" height="1101" alt="image" src="https://github.com/user-attachments/assets/85527c11-e6f5-46cc-a95f-b21a6c5d574a" />

This took me to another page (photo below)
- Selected the "Windows Installer" 64-bit
<img width="1596" height="1270" alt="image" src="https://github.com/user-attachments/assets/423e5c2a-15a1-4504-bed0-25fda0b79cb9" />

- Go to downloads folder within file explorer
- Click to highlight virtual box application then right click and "run as administrator"
<img width="1123" height="627" alt="image" src="https://github.com/user-attachments/assets/3123cc4d-b1a3-4847-a856-af59af948c29" />

- Oracle VirtualBox 7.1.12 Setup box will pop up then click next
<img width="493" height="391" alt="image" src="https://github.com/user-attachments/assets/fc21e5fd-f195-4b45-a236-6ebe60e721fc" />

- Accept the Terms in the License Agreement then click next
<img width="490" height="389" alt="image" src="https://github.com/user-attachments/assets/9e05ec5f-4179-4136-ba70-7656e0b392db" />

- I did not make any changes on the screenshot below then clicked next
<img width="493" height="387" alt="image" src="https://github.com/user-attachments/assets/dfc695e5-76cd-4033-9e61-e82ab53f09a7" />

- Select "yes"
<img width="489" height="385" alt="image" src="https://github.com/user-attachments/assets/a38c3d92-2e0a-4f4a-ba86-c5ca87a20387" />

- Select "yes"
<img width="490" height="391" alt="image" src="https://github.com/user-attachments/assets/58dc2dc5-ab20-4725-9fbd-cd7f6313a951" />

- I left all boxes checked and clicked next
<img width="490" height="388" alt="image" src="https://github.com/user-attachments/assets/5336c1e3-83a5-476b-a019-739ab9ad0e0e" />

- Click "install"
<img width="490" height="384" alt="image" src="https://github.com/user-attachments/assets/a4605785-d336-4a2d-a334-c620d91a26e2" />

- Click "finish"
<img width="490" height="386" alt="image" src="https://github.com/user-attachments/assets/8534d522-4cf3-4fd8-8245-3449f4ddfe45" />


Installing Windows 11 Disk Image (ISO)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Next, download windows 11 installation media on the virtual machine.
- Navigate to https://www.microsoft.com/en-us/software-download/windows11
  
<img width="951" height="1028" alt="image" src="https://github.com/user-attachments/assets/473ec54a-74d1-4674-abf6-d0abb3727765" />


- Drop down to select Windows 11 (multi-edition ISO for x64 devices)
- Click confirm under "Download Windows 11 Disk Image (ISO) for x64 devices"

<img width="931" height="706" alt="image" src="https://github.com/user-attachments/assets/16f2fe5f-45cf-437d-996a-7686a9ecd7d6" />

- Then select product language, I used "English (United States) for my example.
- Then Confirm

<img width="927" height="484" alt="image" src="https://github.com/user-attachments/assets/b31dca5f-9312-4d4d-93d4-dd019d316a05" />

- Click 64-bit Download


Open Virtual box applicaiton
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1270" height="726" alt="image" src="https://github.com/user-attachments/assets/49c508b8-e559-4326-b791-2d2bd0143814" />

- Click New

<img width="753" height="449" alt="image" src="https://github.com/user-attachments/assets/0ef12113-cd5d-46a6-8f4e-ef490070c1ae" />

- Name your VM
- Search for your downloaded ISO image
- Then hit Next

<img width="761" height="455" alt="image" src="https://github.com/user-attachments/assets/8552bac7-0598-4bd4-9bd9-5933e90bed6e" />

- Create a username and password, then click Next

- Based on your PC specs, select the base memory and processer amount, then click Next

<img width="759" height="457" alt="image" src="https://github.com/user-attachments/assets/feb0fec6-8ed1-4a14-8935-d50d3ad1392d" />

- You will apply the same rule to the Virtual hard disk, then next

<img width="755" height="455" alt="image" src="https://github.com/user-attachments/assets/ef7aa256-6729-4eca-90ae-d2171a365384" />

- click Finish

<img width="1014" height="839" alt="image" src="https://github.com/user-attachments/assets/54f5eed9-fcab-4e63-9297-e6fa408c74d0" />

- Click "I dont have a product key"

<img width="1024" height="833" alt="image" src="https://github.com/user-attachments/assets/e5901dd7-a472-43af-bb9c-e70699ea309d" />

- Wait for Windows 11 to finish installing. This will take a few minutes to complete

<img width="1023" height="770" alt="image" src="https://github.com/user-attachments/assets/647005d4-28df-4754-949b-8bb7ee0d2cb9" />

- Download Proton VPN for windows
- https://protonvpn.com/download-windows

<img width="1021" height="764" alt="image" src="https://github.com/user-attachments/assets/65fbf6e5-ec30-481a-9b31-beed90d039f5" />

- Then launch the application from the download history

<img width="1023" height="769" alt="image" src="https://github.com/user-attachments/assets/775a34e6-fff4-4a3e-aa5a-72f02ae437db" />

<img width="1024" height="767" alt="image" src="https://github.com/user-attachments/assets/25674ee5-539e-4523-bc3f-756610922141" />

- Then install, I unchecked the first 3 boxes

- Launched Proton VPN and logged in, then connected to VPN

<img width="1023" height="768" alt="image" src="https://github.com/user-attachments/assets/4d4852b0-4f60-431c-b6be-0eafb3ef5f73" />

- Did a search for my public IP address on https://whatismyipaddress.com/

<img width="1023" height="766" alt="image" src="https://github.com/user-attachments/assets/9e1438d8-2249-4841-801c-fb32b0306dc5" />

- I can see that my public IP address shows the VPN IP on my virtual machine
  

Enviroments and Technologies Used
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-  Virtual Box v7.1.12(virtual machine)
-  Windows 11 Disk Image (ISO) x64
-  VPN (Proton VPN)
  

Operating Systems Used
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Windows 11 (25H2)

  
Process
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


