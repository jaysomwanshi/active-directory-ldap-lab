# 🖥️ Active Directory & LDAP Lab — AWS & Windows Server

This repository documents a complete **Active Directory lab setup** on **AWS EC2** with **LDAP concepts**, showing step-by-step deployment, configuration, and verification.  
All tasks are **fully documented** with **inline screenshots**, making it a useful **portfolio project** and a hands-on learning resource.

---

## 📂 Lab Structure

1. **AWS EC2 Instance Creating**
   - Provisioning an EC2 Windows Server instance.
   - Configuring security groups, RDP access, and connectivity.

2. **Active Directory Installation & Promoting**
   - Installing AD DS role.
   - Promoting the server to a Domain Controller.
   - Setting up forest, domain, and DNS.
   - Verifying installation.

3. **Organizational Unit Creation**
   - Designing a logical structure for users, computers, and groups.
   - Creating and managing OUs.

4. **User Creation**
   - Adding domain users.
   - Configuring passwords and permissions.

5. **Group Creation & Adding to GPO**
   - Creating security groups.
   - Linking them to Group Policy Objects for access control.

6. **Disable USB via GPO**
   - Implementing security policies to block USB storage devices.

7. **Windows DNS and SRV Record Verification**
   - Checking `_ldap._tcp`, `_kerberos._tcp`, and other SRV records for domain health.

8. **Git Initialization**
   - Version control setup for lab documentation.

---

## 🛠 Skills Demonstrated

- **AWS Cloud**: EC2 provisioning, security group configuration.
- **Windows Server Administration**: AD DS installation, DNS setup.
- **Active Directory Management**: OUs, users, and group management.
- **Group Policy**: Creation, linking, and enforcement.
- **DNS & SRV Record Troubleshooting**.
- **Security Hardening**: USB device restrictions.
- **Version Control**: Git repo creation and management.

---

## 📸 Screenshots

### 1️⃣ Active Directory Installation & Promoting
![Backup Server](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Backup%20Server.PNG)
![DSRM Password](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/DSRM%20Password.PNG)
![Forest Name](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Forest%20Name.PNG)
![Installation Complete](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Installation%20Complete.PNG)
![NETBIOS NAME](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/NETBIOS%20NAME.PNG)
![Prequisites Check](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Prequisites%20Check.PNG)
![Promote Server](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Promote%20Server.PNG)
![Review Options](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Review%20Options.PNG)
![Step 1](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Step%201.PNG)
![Step 2](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Step%202.PNG)
![Step 3](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Step%203.PNG)
![Step 4](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Step%204.PNG)
![Step 5](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Step%205.PNG)
![Step 6](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Step%206.PNG)
![Step 7](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Step%207.PNG)
![Windows Server](Git%20Images/Active%20Directory%20Installation%20%26%20Promoting/Windows%20Server.PNG)

---

### 2️⃣ Creating Users
![Create User Shiva 2](Git%20Images/Creating%20Users/Create%20User%20Shiva%202.PNG)
![Create User Shiva 3](Git%20Images/Creating%20Users/Create%20User%20Shiva%203.PNG)
![Create User Shiva](Git%20Images/Creating%20Users/Create%20User%20Shiva.PNG)
![New User](Git%20Images/Creating%20Users/New%20User.PNG)
![User Create 2](Git%20Images/Creating%20Users/User%20Create%202.PNG)
![User Create 3](Git%20Images/Creating%20Users/User%20Create%203.PNG)
![User Create 4](Git%20Images/Creating%20Users/User%20Create%204.PNG)

---

### 3️⃣ Disable USB via GPO
![Disable USB](Git%20Images/Disable_USB_GPO/Disabe%20USB.PNG)
![Disable USB Edit](Git%20Images/Disable_USB_GPO/Disabe%20USB_EDIT.PNG)
![Disable USB Edit 1](Git%20Images/Disable_USB_GPO/Disabe%20USB_EDIT_1.PNG)
![Disable USB Edit 2](Git%20Images/Disable_USB_GPO/Disabe%20USB_EDIT_2.PNG)
![Disable USB Edit 3](Git%20Images/Disable_USB_GPO/Disabe%20USB_EDIT_3.PNG)
![GPO 1](Git%20Images/Disable_USB_GPO/GPO%201.PNG)

---

### 4️⃣ Git Initialized
![Screenshot 1](Git%20Images/Git%20Initialized/Screenshot%202025-08-11%20184623.png)
![Screenshot 2](Git%20Images/Git%20Initialized/Screenshot%202025-08-11%20184649.png)
![Screenshot 3](Git%20Images/Git%20Initialized/Screenshot%202025-08-11%20184722.png)
![Screenshot 4](Git%20Images/Git%20Initialized/Screenshot%202025-08-11%20185008.png)
![Screenshot 5](Git%20Images/Git%20Initialized/Screenshot%202025-08-11%20190455.png)

---

### 5️⃣ Group Created & Added to GPO
![Desktop Wallpaper](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/Desktop_Wallpaper.PNG)
![Desktop Wallpaper Policy](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/Desktop_Wallpaper_policy.PNG)
![Desktop Wallpaper Policy 1](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/Desktop_Wallpaper_policy_1.PNG)
![Desktop Wallpaper Policy 2](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/Desktop_Wallpaper_policy_2.PNG)
![Desktop Wallpaper Policy 3](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/Desktop_Wallpaper_policy_3.PNG)
![GPO](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/GPO.PNG)
![Group 1](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/Group%201.PNG)
![Group 2](Git%20Images/Group%20Created%20%26%20Added%20to%20GPO/Group%202.PNG)
...

---

### 6️⃣ Organizational Unit
![OU Created](Git%20Images/Organizational%20Unit/Organizational%20Unit%20Created.PNG)
![OU Marketing](Git%20Images/Organizational%20Unit/Organizational%20Unit%20Marketing.PNG)
![OU Name](Git%20Images/Organizational%20Unit/Organizational%20Unit%20Name.PNG)
![OU](Git%20Images/Organizational%20Unit/Organizational%20Unit.PNG)

---

### 7️⃣ Windows DNS and SRV Record Verification
![DNS 1](Git%20Images/Windows%20DNS%20and%20SRV%20Record%20Verification/DNS%201.PNG)
![DNS 2](Git%20Images/Windows%20DNS%20and%20SRV%20Record%20Verification/DNS%202.PNG)
![DNS 3](Git%20Images/Windows%20DNS%20and%20SRV%20Record%20Verification/DNS%203.PNG)
![DNS 4](Git%20Images/Windows%20DNS%20and%20SRV%20Record%20Verification/DNS%204.PNG)
![DNS](Git%20Images/Windows%20DNS%20and%20SRV%20Record%20Verification/DNS.PNG)

---

## 📥 How to Use
```bash
# Clone the repo
git clone https://github.com/jaysomwanshi/active-directory-ldap-lab.git
cd active-directory-ldap-lab
