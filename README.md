# 🛡️ Cloud Security IAM Audit

## 📌 Overview
This project is a beginner cloud security lab focused on reviewing AWS IAM configurations to identify common security risks related to user access and permissions. The goal is to simulate real-world scenarios and develop skills in cloud security auditing.

---

## 🎯 Objectives
- Identify risky user permissions
- Analyze access control weaknesses
- Understand IAM security misconfigurations
- Document risks and recommend fixes

---

## 🧰 Tools Used
- AWS Management Console
- IAM (Identity & Access Management)
- Spreadsheet (Risk Register)

---

## 🔍 Methodology

### 🧑‍💻 User Creation & Access Review
Created test users and reviewed assigned permissions.

### 🔐 Permission Analysis
Checked for excessive privileges such as full administrative access.

### 🧠 Risk Identification
Analyzed potential security risks based on IAM configurations.

### 🧾 Documentation
Recorded findings and mitigation strategies in a structured format.

---

## ⚠️ Risks Identified

### 🔴 Admin Access Without MFA
- 🔍 Issue: User has full administrative access (AdministratorAccess)
- 🚨 Risk: If credentials are compromised, attacker gains full control of the account
- 💥 Impact: Data loss, system takeover, service disruption
- 🔐 Fix: Enable Multi-Factor Authentication (MFA) and limit permissions

---

### 🟡 Weak Password Policy
- ⚠️ Issue: Password requirements are not strict
- 💥 Risk: Users can create weak, easily guessable passwords
- 🔐 Fix: Enforce strong password policies (length, symbols, numbers)

**Evidence from AWS IAM Account Settings:**
![AWS IAM Password Policy Configuration](https://github.com/melindalee-cyber/Cloud-Security-IAM-Audit-/blob/main/screenshot-weak-password-policy.png?raw=true)

*The screenshot shows the current password policy with only a 6-character minimum requirement and no strength requirements (uppercase, lowercase, numbers, symbols), making it vulnerable to weak passwords.*

---

### 🔴 Unused Admin Account
- 🔍 Issue: Admin-level user exists but is not actively used
- 🚨 Risk: Unused accounts can be exploited without detection
- 💥 Impact: Unauthorized access to systems and data
- 🔐 Fix: Remove inactive users or reduce permissions

---

## 📊 Key Takeaways
- Excessive permissions increase security risk
- MFA is critical for protecting accounts
- Regular user audits are necessary
- Strong password policies reduce attack risk

---

## 🧠 Skills Demonstrated
- Cloud security fundamentals
- Risk identification and analysis
- Access control evaluation
- Security best practices awareness
- Technical-to-business risk translation

---

## 📁 Project Structure
- `README.md` - Project documentation and findings
- `screenshot-weak-password-policy.png` - Evidence of weak IAM password policy configuration

---

## 🚀 Outcome
This project demonstrates a foundational understanding of cloud security and IAM risk management by identifying common misconfigurations and proposing mitigation strategies. It reflects real-world security challenges and the importance of regular auditing and policy enforcement.

---

## 📝 Notes
This project was created for learning and professional development purposes in a controlled environment.
