<div align="center">

# 🛡️ Vulnerability Report  
**Security Disclosure | Data Breach Log**  
*Discovered & Reported by [@keccy](https://t.me/keccy) | [veccy.my.id](https://veccy.my.id)*  

<img src="https://img.shields.io/badge/Status-Disclosed-blueviolet?style=for-the-badge"/>  
<img src="https://img.shields.io/badge/Affected_Records-4897%2B-critical?style=for-the-badge&color=crimson"/>  
[![Download](https://img.shields.io/badge/Download-Data%20Leak-critical?style=for-the-badge&logo=github)](https://github.com/qeize/leaked/releases/tag/data)

---

</div>

## Summary

On **February 10, 2025 at 02:35 AM (GMT+7)**, a critical injection vulnerability was identified on the student registration portal:

> **Website:** [https://ppdb.smansumsel.sch.id](https://ppdb.smansumsel.sch.id)  
> **Impact:** Unauthorized access to over 4,897 student records.

The exploit allowed full access to the database containing sensitive personal and academic information.

---

## Extracted Data

The breach includes the following fields per record:

- Full Name  
- NISN (National Student ID Number)  
- NIK (National Identity Number)  
- Date of Birth  
- Address  
- Phone Number  
- Parent/Guardian Full Data  
- Family Economic Background  
- Other Identifiable Student Information  

---

## Technical Context

The vulnerability stems from insufficient input validation, allowing direct database access via injection techniques. No authorization or session layer was detected during the session, enabling unrestricted data dumping.

---

## Disclosure Intent

> This report is published **for cybersecurity awareness and educational purposes**.  
> The goal is to raise concerns regarding student data privacy and advocate for better infrastructure security in public systems.  
> **No data has been sold, leaked, or used for harm.**

---

## Contact & Credits

- **Researcher:** [@keccy](https://t.me/keccy)  
- **Site:** [https://veccy.my.id](https://veccy.my.id)  
- **Death Networks**
---

<div align="center">
© 2020–2025 Veccy | All rights reserved.
</div>
