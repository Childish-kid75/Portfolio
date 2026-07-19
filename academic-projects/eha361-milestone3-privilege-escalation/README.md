
### **Milestone 3: Privilege Escalation Attack**

```markdown
# Privilege Escalation Attack (EHA361 - Milestone 3)

## 📋 Overview
Successful privilege escalation from normal user to root using SUID misconfiguration on Kali Linux.

## 🎯 Key Achievements
- ✅ Escalated from normal user (UID 1000) to root (UID 0)
- ✅ Demonstrated CVE-2021-4034 (PwnKit) is patched
- ✅ Exploited SUID binary misconfiguration
- ✅ Documented mitigations

## 🛠️ Technologies Used
- Kali Linux 2025.4
- C Programming
- SUID binary exploitation

## 🔧 Attack Steps
1. Created C program with setuid(0)
2. Set SUID bit with root ownership
3. Executed binary to get root shell
4. Verified root access on /etc/shadow

## 📄 Full Report
[View Complete Report](EHA361_Milestone%203_Tshiamo%20Mosweu%20.pdf)
