# 🛠️ Multi-Boot USB Creation Guide 
### Using WinSetupFromUSB

This guide provides a step-by-step walkthrough for creating a single USB drive that can boot multiple Windows ISOs (e.g., Windows 10 Home, Pro, and Windows 11).

---

## 🚀 Step 1: Extract and Run the Tool
1. **Right-click** on `WinSetupFromUSB-1-10.zip` and select **Run as Administrator**.
2. **Extract** the files to your preferred location.
3. Open the folder and locate the correct version:
   * `WinSetupFromUSB_1-10` (for 32-bit systems)
   * `WinSetupFromUSB_1-10_x64` (for 64-bit systems)
4. **Right-click** the `_x64` version and select **Run as Administrator**.

---

## 🔌 Step 2: Connect USB Drive
1. Plug in your USB drive.
2. Click **Refresh**; your USB flash drive will appear in the drop-down menu automatically.

---

## 📀 Step 3: First ISO (Windows 10 Home)
> **Note:** This step prepares and formats the drive.

### ⚙️ Format Settings:
* [x] **Check:** `Auto format it with FBinst`
* [x] **Select:** `NTFS` (Required for modern Windows ISOs)

### 📂 ISO Selection:
1. Check the box: **Windows Vista/7/8/10/Server 2008/2012 based ISO**.
2. Click the **"..."** button and select your **Windows 10 Home ISO**.

### 🏷️ Custom Naming:
1. Click **Advanced Options**.
2. Check **Custom menu names for Vista/7/8/Server Source**.
3. **Close** the Advanced options window (click the **X**).

### ⚡ Execution:
1. Click **GO**.
2. **Folder name:** Enter `winH`.
3. **OS name:** Enter `Win-10(Home)`.
4. Wait for the **"Job done"** message.

---

## ➕ Step 4: Adding Additional ISOs (Pro & Win 11)
**⚠️ IMPORTANT:** For every ISO after the first one, you **MUST NOT** format the drive.

### For Windows 10 Pro:
1. **Uncheck** `Auto format it with FBinst`.
2. Select the **Windows 10 Pro ISO**.
3. **Advanced Options** → Check **Custom menu names...** → Close window.
4. Click **GO**.
   * **Folder name:** `winP`
   * **OS name:** `Win-10(Pro)`

### For Windows 11 Pro:
1. Repeat the same process (Keep Auto-format **unchecked**).
2. Select the **Windows 11 Pro ISO**.
3. Click **GO**.
   * **Folder name:** `win11P`
   * **OS name:** `Win-11(Pro)`

---

## ✅ Final Result
Close the software. Your USB drive is now ready with:
* 🟦 **Windows 10 Home**
* 🟦 **Windows 10 Pro**
* 🟦 **Windows 11 Pro**

**How to use:** Restart your PC, boot from the USB (usually F12, F11, or Esc), and select your desired OS from the menu.
