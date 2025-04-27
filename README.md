# bash-automation
# small bash script to automate some work stuff 

# Disk Cleanup Script

This script performs essential disk maintenance tasks, including:

- 🗑️ **Clearing temporary files** (user & system)  
- 🔄 **Removing Windows Update cache**  
- 🗂️ **Deleting prefetch files**  
- 🗑️ **Emptying the Recycle Bin**  
- 🔍 **Running chkdsk** for disk error checking  
- 🧹 **Executing Windows Disk Cleanup** (`cleanmgr`)

---

## ⚙️ Requirements

- Windows 7 / 10 / 11  
- Administrator rights  
- Command Prompt (Run as Admin)

---

## 🚀 How to Use

1. **Download the Script**  
   Copy the script into a text file and save it as `disk_cleanup.bat`.  
   (Or download directly if provided.)

2. **Run as Administrator**  
   - Right-click `disk_cleanup.bat` → **Run as Administrator**  
   - OR open an elevated Command Prompt and run:
   ```bat
   cd \path\to\script
   disk_cleanup.bat

