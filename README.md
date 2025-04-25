# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration

# AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

# DESIGN STEPS:
### Step 1: Install VirtualBox
🔗 Installation Steps: 1.Download the Windows hosts .exe file from the official VirtualBox website. 2.Run the installer and follow the on-screen instructions. 3.Once installed, launch VirtualBox to verify the installation.

### Step 2: Install Kali Linux on VirtualBox
🔗 Download Kali Linux VM: Click Here

Installation Steps: 1.Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit). 2.Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 3.Go to Settings > Storage, click Empty under Controller: IDE. 4.Select Graphical Install, follow the prompts to set language, location, username, and password. 5.Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.

### Step 3: Install Autopsy (GUI-based Forensic Tool)
🔗 Download Autopsy: Click Here

Installation Steps: Download the Autopsy Windows Installer from the official website. Extract the ZIP file and open the bin folder. Run autopsy.exe and set up a new forensic case for analysis.

### Step 4: Install Sleuth Kit (CLI-based Forensic Tools)
🔗 Download Sleuth Kit: Click Here

# Installation Steps: 
1.Download the Windows ZIP package from the official website. 
2.Extract the ZIP folder and move it to a suitable directory (e.g., C:\sleuthkit). 
3.Add the bin folder to Windows PATH: 
4.Open Control Panel → System → Advanced System Settings. 
5.Click Environment Variables → Edit Path. 
6.Add the Sleuth Kit bin folder path and save changes. 
7.Verify installation by running:

```fls -version```

### Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows
1.Press Win + X, Select Disk Management. 
2.Click Action > Create VHD. 
3.Choose a location and set a disk size (e.g., 10GB+). 
4.Select Fixed Size or Dynamically Expanding and click OK. 
5.In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select MBR. 
6.Right-click Unallocated Space → New Simple Volume → Format the disk -> Click next → Finish.

## OUTPUT:
File and Folder Configuration Analysis Results
## Virtual Box:
![1](https://github.com/user-attachments/assets/5767c6da-e828-4bfa-a755-0cb1b178567f)
## VIRTUAL Machine(Kali Linux):
![2](https://github.com/user-attachments/assets/e14d1e17-33ee-4866-a86f-931d06182aa6)
## AUTOPSY:
![3](https://github.com/user-attachments/assets/afd1c198-ac52-4356-a3bc-55fe1ba32aa7)
## Sleuthkit:
![4](https://github.com/user-attachments/assets/0ed99af4-6457-4046-b02c-f84d63278496)
## creation of virtual hard disk:
![5](https://github.com/user-attachments/assets/516be48b-6718-484d-99fa-d0e7b2c6bdfb)
## analysis of images:
![6](https://github.com/user-attachments/assets/44aba685-40de-416b-b73d-530e110437d4)
## click on os account:
![7](https://github.com/user-attachments/assets/8a9dba43-14b9-4f5f-be66-e36d40b7af31)
# GENERATE REPORTS:
![8](https://github.com/user-attachments/assets/6de53939-30ca-4b0a-90cf-5aeaa5d8776c)
![9](https://github.com/user-attachments/assets/0cf837df-7e84-415f-bb1f-e0785848690e)
![10](https://github.com/user-attachments/assets/2d4064fe-7b18-43cb-b72e-0bbcf7f4dc7f)

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
