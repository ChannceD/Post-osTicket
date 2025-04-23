<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# 🧾 osTicket Post-Installation Lab – System Configuration Walkthrough

After deploying osTicket, the next step is setting it up for actual use. In this lab, I configured core components like roles, agents, departments, teams, SLAs, and help topics. These are essential tasks for real-world help desk administration.

---

## ⚙️ Technologies Used

- **osTicket** – Open-source support ticket system
- **Windows 10 VM** – Running the osTicket instance
- **Web GUI** – Used to configure the ticket system post-deployment

---

## Step-by-Step Configuration (with Screenshots)

### 🔹 Step 1: Getting Started
![Step 1](osTicket-Lab-Post/1.Getting%20started.png)  
Access the osTicket admin dashboard after installation to begin setup.

---

### 🔹 Step 2–3: Create a New Role
![Step 2](osTicket-Lab-Post/2.Creating%20new%20role.png)  
![Step 3](osTicket-Lab-Post/3.Adding%20new%20Role.png)  
Navigate to **Admin Panel > Agents > Roles** to create a new role (e.g., Technician).

---

### 🔹 Step 4: Set Role Permissions
![Step 4](osTicket-Lab-Post/4.Setting%20permissions.png)  
Assign what this role is allowed to do — e.g., manage tickets, view users, etc.

---

### 🔹 Step 5: Confirm Role Creation
![Step 5](osTicket-Lab-Post/5.successfully%20added%20new%20role.png)  
Role successfully created and ready to be assigned to agents.

---

### 🔹 Step 6–7: Add a Department
![Step 6](osTicket-Lab-Post/6.Adding%20new%20Deparment%20.png)  
![Step 7](osTicket-Lab-Post/7.New%20deparment%20Creation.png)  
Go to **Departments** and add one (e.g., IT Support) to help organize ticket flow.

---

### 🔹 Step 8: Create a Team
![Step 8](osTicket-Lab-Post/8.Adding%20a%20new%20Team%20.png)  
Teams allow grouping agents for managing certain ticket types or topics.

---

### 🔹 Step 9: Uncheck Registration Requirement
![Step 9](osTicket-Lab-Post/9.Uncheck%20Registration%20Required.png)  
Allow users to submit tickets without registering an account by unchecking this box.

---

### 🔹 Step 10–11: Add a New Agent & Set Password
![Step 10](osTicket-Lab-Post/10.Creating%20new%20agent.png)  
![Step 11](osTicket-Lab-Post/11.Setting%20agents%20passwords.png)  
Create a new agent (help desk staff) and assign the new role and department.

---

### 🔹 Step 12: Add a New User
![Step 12](osTicket-Lab-Post/12.Adding%20a%20new%20user.png)  
Users are the clients or employees who will submit tickets.

---

### 🔹 Step 13: Add SLA Plan
![Step 13](osTicket-Lab-Post/13.Adding%20SLA.png)  
Define Service Level Agreements — like response/resolution time for tickets.

---

### 🔹 Step 14: Create Help Topic
![Step 14](osTicket-Lab-Post/14.New%20help%20topic%20.png)  
Help Topics guide users to select the right category when submitting a ticket.

---

### 🔹 Step 15: Setup Complete
![Step 15](osTicket-Lab-Post/15.Finished%20.png)  
osTicket is now fully configured and ready for real help desk operation.

---

## 🚀 Skills Demonstrated

- osTicket Admin Configuration
- Role-Based Access Control (RBAC)
- Department and Team Structuring
- SLA and Workflow Design
- User and Agent Management
- Help Desk System Customization

---

## 💼 Why This Matters

Knowing how to install software is great — but configuring it for actual use is where IT support pros shine. This lab shows I can manage and customize a real-world ticketing system for internal IT support or MSP environments.

---
