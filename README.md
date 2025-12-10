# Windows-Event-Viewer-Basics

## 📖 Overview
This lab provides a straightforward introduction to using **Windows Event Viewer** for security log analysis.  
The goal is to learn how to navigate Event Viewer, filter logs by specific Event IDs, and interpret security-related events.

**Screenshots located in Screenshots Folder in the correct order**

---

## 🛠️ Lab Steps

### 1. Open Event Viewer
- Navigate to **Windows Logs > Security**  

---

### 2. Filter Current Log
- Apply a filter for **Event ID 4625** (failed login attempts).  

---

### 3. Review Failed Login Event
- Observe a failed login recorded at **1:20:03 PM**.  

---

### 4. Check Password Policy Modification
- Navigate to **Event ID 4739**.  
- Notice the password policy was modified at **1:46:36 PM**.  

---

### 5. Identify Group Membership Changes
- Navigate to **Event ID 4732**.  
- A new user was added to a **security-enabled local group**.  

---

## 🎯 Purpose
By completing this lab, we will:
- Understand how to navigate **Windows Event Viewer**.
- Learn to filter logs by **specific Event IDs**.
- Gain insight into common security events such as failed logins, password policy changes, and group membership modifications.

---

## ✅ Key Takeaways
- **Event ID 4625** → Failed login attempt  
- **Event ID 4739** → Password policy modification  
- **Event ID 4732** → User added to security-enabled local group  

---



