<img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/c0201915-4b89-48b6-a6d3-4abecf2d563b" />

---

# 🚀 Post‑Installation Configuration

This tutorial demonstrates the **post‑installation setup** of the osTicket system. You’ll learn how to:

1. Create agent **Roles**  
2. Organize agents into **Departments**  
3. Build specialized **Teams**  
4. Allow public ticket creation in **User Settings**  
5. Add **Agents** to the system  
6. Register **Customer Users**  
7. Define **SLA Plans**  
8. Create **Help Topics**

---

## 1️⃣ Create a New Role

Go to **Admin Panel → Agents → Roles**

1. Click **Add New Role**  
2. Enter **Role Name**: `Supreme Admin`  
3. Grant **All Permissions**  
4. Click **Save Changes**

> 📌 _Roles control what an agent can see and do._

<img width="1262" height="431" alt="image" src="https://github.com/user-attachments/assets/b1f4e80c-4e36-4f33-b99f-b2d4a214a9b7" />  
*Figure 1: Adding the “Supreme Admin” role with full access.*

---

## 2️⃣ Create a Department

Go to **Admin Panel → Agents → Departments**

- Click **Add New Department**  
- Enter **Department Name**: `System Administrators`  
- (Optional) Configure SLAs, Managers, and email notifications  
- Click **Save Changes**

> 📌 _Departments group agents by function for better ticket routing._

<img width="1053" height="854" alt="image" src="https://github.com/user-attachments/assets/81309c4d-2d32-4022-9b78-782bf7005c4f" />  
*Figure 2: Defining the “System Administrators” department.*

---

## 3️⃣ Set Up a Team

Go to **Admin Panel → Agents → Teams**

1. Click **Add New Team**  
2. Enter **Team Name**: `Level II Support`  
3. Select agents from relevant departments  
4. Click **Save Changes**

> ⚠️ _Teams combine agents from multiple departments for specialized workflows._

<img width="1261" height="781" alt="image" src="https://github.com/user-attachments/assets/a6f28ba6-f08c-488f-bccb-e51ea80829f0" />  
*Figure 3: Configuring the “Level II Support” team.*

---

## 4️⃣ Allow Public Ticket Creation

Go to **Admin Panel → Settings → User Settings**

- Check **“Allow users to create tickets”**  
- Click **Save Settings**

> 📌 _This enables customers to open tickets via the web portal._

<img width="1265" height="766" alt="image" src="https://github.com/user-attachments/assets/48c98cd1-f70f-417c-91a3-e7c28e2388e0" />  
*Figure 4: Enabling end users to create tickets.*

---

## 5️⃣ Add Agents

Go to **Admin Panel → Agents → Agents**

1. Click **Add New Agent**  
2. Fill in **Name**, **Email**, and **Username**  
3. Assign **Primary Department**: `System Administrators`  
4. Assign **Role**: `Supreme Admin`  
5. (Optional) Add extra departments or teams  
6. Click **Save Changes**

> 📌 _Agents are help desk staff who handle tickets._

<img width="952" height="832" alt="image" src="https://github.com/user-attachments/assets/7ed93b06-2933-4eaa-8f7d-aa4428a31e40" />  
*Figure 5: Adding a new agent.*

---

## 6️⃣ Register Customer Users

Go to **Agent Panel → Users → User Directory → Add New**

- Enter **User Name** and **Email Address**  
- Click **Save**

> 📌 _Users (customers) open tickets; they’re identified by email._

<img width="1236" height="417" alt="image" src="https://github.com/user-attachments/assets/08a0740e-f4d7-4b3f-90ab-f7c4e559b428" />  
*Figure 6: Registering a new customer user.*

---

## 7️⃣ Configure SLA Plans

Go to **Admin Panel → Manage → SLA Plans**

1. Click **Add New SLA Plan**  
2. Enter **Plan Name**: `SEV-A`  
3. Set **Schedule**: `24/7`  
4. Set **Grace Period**: `1 hour`  
5. Click **Save**

> 📌 _SLA Plans define expected response times by severity._

<img width="1227" height="740" alt="image" src="https://github.com/user-attachments/assets/d9852bf3-35db-4bd0-a3bc-e54a754c82eb" />  
*Figure 7: Setting up the “SEV‑A” SLA plan.*

---

## 8️⃣ Define Help Topics

Go to **Help Topics**

1. Click **Add Help Topic**  
2. Enter **Topic Name**: `Business Critical Outage`  
3. Assign to relevant **Teams** or **Departments**  
4. Click **Save**

> 📌 _Help topics let users categorize tickets for faster routing._

<img width="1212" height="702" alt="image" src="https://github.com/user-attachments/assets/cc77943c-b93a-4d42-b099-008667e9dd27" />  
*Figure 8: Adding the “Business Critical Outage” help topic.*

---

## 🎉 Next Steps

- Dive into **Ticket Lifecycle** settings (auto‑assignments, escalations)  
- Customize **Email Templates** for branding  
- Generate **Reports** and **Analytics**  

**Happy ticketing!**
