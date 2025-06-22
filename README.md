# 💻 PowerShell-Fundamentals-Lab 🧪

This repository documents my hands-on journey learning PowerShell from the ground up. It is divided into **three progressive phases**, beginning with system discovery and ending with a capstone project. All commands and scripts are **beginner-safe** and crafted for real-world, practical experience.

---

## 🔍 Phase 1: Discovery  
**Goal:** Learn the PowerShell environment and explore system information without making any system changes.

### ✅ Steps:
- 🖥️ Open PowerShell as Administrator  
- 🔢 Check the installed PowerShell version using `$PSVersionTable`  
- 📁 Navigate the file system with `Get-ChildItem` and `Set-Location`  
- 📚 Use the built-in help system with `Get-Help`  
- ⚙️ View system information with `Get-ComputerInfo`, `Get-Process`, and `Get-Service`  
- 📝 Export output to a file using `Out-File`  

---

## ⚙️ Phase 2: Configuration & Automation  
**Goal:** Make small, safe system customizations and automate simple tasks using scripts.

### ✅ Steps:
- 🔁 Create and use aliases with `Set-Alias`  
- 🧾 Create and run `.ps1` script files using `Write-Host`  
- 🧠 Customize the PowerShell prompt using a custom `function`  
- 🗓️ Schedule a script to run at login using Scheduled Task cmdlets  

---

## 🧠 Phase 3: Capstone – System Audit Tool  
**Goal:** Build a tool that collects system data and exports it to text and HTML reports.

### 📋 This script will:
- 📊 Collect the top CPU-consuming processes  
- 💾 Check disk usage  
- 🛑 List stopped services  
- 🌐 Generate an HTML report of all services  
- 📂 Save everything into a timestamped folder on the Desktop  

📁 Script location: `Phase3_Capstone/System_Audit_Report.ps1`

---

## 🧾 What I Learned

- 🧭 How to navigate and query system data using PowerShell commands  
- 🧪 How to write and execute PowerShell scripts  
- 🛠️ How to automate tasks using scheduled jobs  
- 📈 How to collect and format data into useful reports  
- 📂 How to structure a PowerShell project for GitHub and portfolio use  

---

## 🚀 Usage Instructions

1. 📥 Clone or download the repository  
2. 🧑‍💻 Open PowerShell as Administrator  
3. 🧱 Run the scripts phase by phase or jump into the final project  
4. ✏️ Customize and expand any script to make it your own  

> ⚠️ All scripts in this project are safe for educational and beginner use.

---

## 🗂️ Folder Structure

