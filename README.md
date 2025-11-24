# <center>🛠️ **Ansible Hands‑On Labs — Zero to Hero Series**</center>

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7898d4d6-e762-4a95-af40-f64578235576" />


## 👤 **Author: Sandeep Kumar Sharma**

A complete end‑to‑end Ansible learning series designed to take beginners to an advanced, production‑ready automation level.

---

# 🚀 **Welcome to the Ultimate Ansible Hands‑On Repository!**

This repository contains a **complete, structured, deeply practical Ansible training series** with **step‑by‑step labs**, real‑world examples, and production‑ready automation practices.

If you are:

* A beginner trying to learn Ansible from scratch,
* A working professional preparing for real project automation,
* A DevOps engineer wanting hands‑on practice,

👉 **Then this is the perfect place for you.**

Every lab is written in a clean, classroom‑style, easy‑to‑understand format with:

* Full explanations
* Deep concepts
* Hands‑on exercises
* Separate folders
* Real‑world scenarios

---

# 📚 **What You Will Learn**

This series covers everything from basics to production-level automation:

### ✔️ Installation & Setup

### ✔️ Inventory Management (Static + Dynamic)

### ✔️ Ad‑hoc Commands

### ✔️ Playbooks & YAML Structure

### ✔️ Variables, Loops, Conditionals

### ✔️ Templates (Jinja2)

### ✔️ Handlers, Task Control, Error Handling

### ✔️ Roles, Role Dependencies, Best Practices

### ✔️ Galaxy Roles & Collections

### ✔️ Facts, Filters, Custom Facts

### ✔️ Block, Rescue & Always

### ✔️ Delegation & Orchestration

### ✔️ Advanced Automation Patterns

---

# 🧩 **Lab Index — Zero to Hero (Complete List)**

Each lab is self‑contained and easy to execute.

| Lab No.      | Lab Title                                                       |
| ------------ | --------------------------------------------------------------- |
| **Lab 1**    | Install & Configure Ansible (Ubuntu + Amazon Linux)             |
| **Lab 2**    | Setting Up SSH Passwordless Access + Inventory Setup            |
| **Lab 3**    | Ad‑hoc Commands (20 Real‑World Examples)                        |
| **Lab 4**    | Basic Facts & Fact Gathering                                    |
| **Lab 5**    | Connectivity Testing (ping, shell, copy, file)                  |
| **Lab 6**    | Writing Your First Playbook + Structure Explained               |
| **Lab 7**    | Variables (`vars`, `vars_files`, `vars_prompt`, Inventory Vars) |
| **Lab 8**    | Conditionals & When Statements                                  |
| **Lab 9**    | Loops (`loop`, dictionary loops)                                |
| **Lab 10**   | Templates (Jinja2 Templates)                                    |
| **Lab 11**   | Handlers & Notifications                                        |
| **Lab 12**   | Error Handling (`ignore_errors`, `failed_when`, `changed_when`) |
| **Lab 13**   | Advanced Facts, Filters, Fact Caching, Custom Facts             |
| **Lab 14**   | Creating Roles (Beginner to Intermediate)                       |
| **Lab 14.2** | Deep‑Dive Role Architecture + Best Practices                    |
| **Lab 15**   | Role Dependencies & Advanced Composition                        |
| **Lab 16**   | Using Ansible Galaxy                                            |
| **Lab 17**   | Dynamic Inventory (AWS + Custom Script)                         |
| **Lab 18**   | Block, Rescue & Always                                          |
| **Lab 19**   | Delegation (`delegate_to`, `run_once`, `local_action`)          |
| **Lab 20**   | (Coming Soon…)                                                  |

---

# 📦 **Repository Structure**

Your repo will look like:

```
ansible-labs/
├── lab-01-installation/
├── lab-02-inventory-setup/
├── lab-03-ad-hoc-commands/
├── lab-04-facts/
├── ...
└── README.md
```

Each lab has:

* `lab.md` (instructions)
* `playbooks/` folder (if applicable)
* `templates/`, `roles/`, etc.

---

# 🛠 **Requirements**

You only need:

* Ubuntu/Amazon Linux machines (cloud or local)
* Python + SSH
* Ansible installed on the control node
* Basic command line knowledge

---

# ▶️ **How to Use This Repository**

Clone the repo:

```
git clone https://github.com/Shyamsandeep28/ansible.git
cd ansible
```

Run any lab:

```
cd lab-03-ad-hoc-commands
ansible all -m ping
```

Playbooks will be inside respective lab folders.

---

# 🌟 **Why This Series Is Special**

* Fully hands‑on, not theory‑heavy
* Real‑world DevOps experience is embedded in each lab
* Step‑by‑step commands that work on both Ubuntu and Amazon Linux
* Deep explanations with clear examples
* Easily digestible even for beginners
* Perfect for interview prep & corporate training

---

# 🧑‍🏫 **About the Author — Sandeep Kumar Sharma**

* DevOps Architect & Trainer
* Delivered 50+ corporate sessions globally
* Expert in Ansible, Terraform, Kubernetes, Docker, AWS, Azure
* Passionate about enabling engineers through hands‑on learning

---

# 🌐 **Connect With Me**

If you enjoy these labs and want to follow more:

#**🔗 LinkedIn**
Connect for DevOps, Cloud, Terraform, Kubernetes, and Databricks updates: 👉 https://www.linkedin.com/in/sandeep-kaushik-2a345856/

#**📝 Medium (Technical Blogs)**
Read my blogs on ADF, Databricks, Terraform, DevOps, and Cloud Architecture: 👉 https://medium.com/@shyamsandeep28



---

# ⭐ **Support the Project**

If this repository helps you:

* ⭐ Star the repo
* 🔄 Share with your friends
* 🤝 Contribute labs or improvements

Every star motivates the next lab! 🌟

---

# 🙌 **Thank You for Learning From This Project**

Enjoy the labs and build world‑class automation skills with Ansible!
