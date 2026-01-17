This guide provides a step-by-step walkthrough for creating a single USB drive that can boot multiple Windows ISOs (e.g., Windows 10 Home, Pro, and Windows 11) using WinSetupFromUSB.

🚀 Step 1: Extract and Run the Tool
Right-click on WinSetupFromUSB-1-10.zip and select Run as Administrator.

Extract the files to your preferred location.

Open the extracted folder. You will see three items:

files

WinSetupFromUSB_1-10 (32-bit)

WinSetupFromUSB_1-10_x64 (64-bit)

Since your OS is 64-bit, right-click WinSetupFromUSB_1-10_x64 and select Run as Administrator.

🔌 Step 2: Connect USB Drive
Plug in your USB drive.

Click Refresh; your USB flash drive should appear automatically in the drop-down menu.

📀 Step 3: First ISO (Windows 10 Home)
Format Settings:

Check Auto format it with FBinst.

Select NTFS (Required for modern Windows ISOs).

ISO Selection:

Check the box for Windows Vista/7/8/10/Server 2008/2012 based ISO.

Click the browse button and select your Windows 10 Home ISO.

Custom Naming:

Click Advanced options.

Check Custom menu names for Vista/7/8/Server Source.

Close the Advanced options window (click the X).

Execution:

Click GO.

When prompted, enter a folder name: (e.g., winH).

When prompted, enter the OS name: (e.g., Win-10(Home)).

Wait for the "Job done" message.

➕ Step 4: Adding Additional ISOs (Windows 10 Pro & 11)
Important: For every ISO after the first one, you must NOT format the drive.

For Windows 10 Pro:
Uncheck Auto format it with FBinst.

Select the Windows 10 Pro ISO.

Go to Advanced options → Check Custom menu names... → Close window.

Click GO.

Folder name: winP

OS name: Win-10(Pro)

Wait for "Job done".

For Windows 11 Pro:
Repeat the same process as the Pro version above.

Select the Windows 11 Pro ISO.

Click GO.

Folder name: win11P

OS name: Win-11(Pro)

Wait for "Job done".

✅ Final Result
Close the software. Your USB drive is now a multi-boot tool containing:

Windows 10 Home

Windows 10 Pro

Windows 11 Pro

To use: Restart your PC, boot from the USB, and select your desired OS from the menu.
