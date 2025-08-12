# Network Troubleshooter PowerShell Script

## Lab Overview
This PowerShell script automates key network troubleshooting tasks commonly performed by help desk technicians. It tests connectivity to the network gateway, verifies DNS resolution, and checks if a specified port on a server is open. Results are displayed in the console and logged to a file for easy documentation.

---

## Lab Objectives
- Practice PowerShell scripting for IT support automation  
- Learn to perform network diagnostics with PowerShell cmdlets  
- Generate clear pass/fail output with logging  
- Build a useful tool to include in a help desk portfolio  

---

## Prerequisites
- Windows 10 or later with PowerShell 5.1+  
- Basic understanding of PowerShell commands  
- Execution Policy set to allow script running (`RemoteSigned` or use `Bypass`)  

---

## Lab Setup & Execution Steps

### Step 1: Download the Script
- Save the `Network_Troubleshooter.ps1` script file to a folder on your computer (e.g., Desktop or Documents).
<img width="1019" height="698" alt="Screenshot 2025-08-12 at 12 27 27 PM" src="https://github.com/user-attachments/assets/95e302c6-f62f-4d8c-9d7b-d1a1fe7ba22a" />

### Step 2: Open PowerShell
- Open PowerShell as Administrator (recommended) or regular user.

### Step 3: Set Execution Policy (if needed)
- Run this command to allow script execution for this session:  
  ```powershell
  Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
  
### Step 4 : Run the Script 
-Navigate to the folder where the script is saved:

- Execute the script:
  
<img width="912" height="606" alt="Screenshot 2025-08-12 at 12 36 59 PM" src="https://github.com/user-attachments/assets/00bd07a7-d735-4a87-8d01-5fc3587288c1" />

### Step 5 : Review Results 
- File Saved to the Desktop after running script
  
<img width="569" height="276" alt="Screenshot 2025-08-12 at 12 38 17 PM" src="https://github.com/user-attachments/assets/252068d1-d0da-4404-b726-c8098c3e47ef" />

