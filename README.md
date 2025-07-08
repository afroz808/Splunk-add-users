# 👥 Splunk SOC Project: User Management for Secure Access

## 🔍 Project Overview

This project focuses on configuring and managing users in Splunk — a vital part of any **Security Operations Center (SOC)** to ensure structured access control and monitoring visibility.

---

## 🛠️ Tools Used

- Splunk (Free version or Enterprise Trial)
- Web UI Interface
- Default roles: admin, power, user

---

## 🎯 Steps to Add a New User in Splunk

1. Navigate to **Settings → Users → New User**  
2. Fill in:
   - Username
   - Full Name
   - Password
   - Email
3. Assign appropriate role (`user`, `power`, or custom role)
4. Click **Save**
5. Go to **Settings → Indexes** and set access permissions (e.g. summary, audit, configtracker)
6. Adjust **Search Limits** under Settings → Roles → Limits  
   > Set to `Infinite` if necessary for that user role
7. Save changes

---

## 🧠 Why User Management Matters in SOC

- 🔐 Enforces Role-Based Access Control (RBAC)  
- 📊 Enables multi-analyst SOC environments  
- ⚠️ Prevents unauthorized access to critical log sources  
- 📁 Supports log separation and privacy


## 📬 Contact

**Author:** Afroz Shaikh  
**Email:** afrozshaikh8086@gmail.com  

