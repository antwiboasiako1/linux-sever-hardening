# 🔐 Linux System Hardening with Python Script

This project demonstrates a step-by-step process of hardening a Linux system using a custom Python script. It includes:
- Creating and running the hardening script
- Verifying firewall rules
- Confirming system configuration
- Ensuring settings persist after reboot

All steps are documented with screenshots for clarity.

---

## 📸 Project Workflow & Screenshots

1. ✅ **Create a file named `harden.sh`**  
   ![Step 1](./1.%20create%20a%20file%20name%20harden.sh%20.png)

2. ✍️ **Write a Python script for hardening**  
   ![Step 2](./2.%20write%20python%20script%20for%20harden.s....png)

3. 🔒 **Change file permission to make script executable**  
   ![Step 3](./3.%20change%20mod%20.png)

4. ▶️ **Run the hardening script**  
   ![Step 4](./4.%20run%20the%20script.png)

5. ⚙️ **Verify the script is running**  
   ![Step 5](./5.%20script%20running.png)

6. ✅ **Confirm system configuration changes**  
   ![Step 6](./6.%20confirm%20configuration%20.png)

7. 🔍 **Preview the configured firewall rules**  
   ![Step 7](./7.%20preview%20FW%20rules.png)

8. 🔁 **Reboot system to test persistence**  
   ![Step 8](./8.%20reboot%20system%20to%20cofigure%20.png)

9. 🔥 **Verify firewall rules remain after reboot**  
   ![Step 9](./9.%20verify%20firewall%20rule%20after%20reboot%20....png)

---

## 🧠 What I Learned

- Automating system hardening tasks with Python and shell scripts
- Setting and verifying firewall rules (likely with `ufw` or `iptables`)
- Importance of making scripts persistent across reboots
- Practical Linux administration and security hygiene

---

## 🛠 Tools & Skills Practiced

- **Linux Command Line**
- **Bash scripting (`chmod`, `sh`)**
- **Python scripting**
- **Firewall configuration**
- **System reboot & config persistence**
- **Basic GitHub documentation**

---

## 📌 Next Steps

- Convert the Python script to run on multiple Linux distros
- Add a logging mechanism to the script
- Create a system hardening checklist for production environments
- Package script as `.deb` for easier deployment

---

## 📂 Repository Structure

```bash
.
├── 1. create a file name harden.sh .png
├── 2. write python script for harden.s....png
├── 3. change mod .png
├── 4. run the script.png
├── 5. script running.png
├── 6. confirm configuration .png
├── 7. preview FW rules.png
├── 8. reboot system to cofigure .png
└── 9. verify firewall rule after reboot ....png
