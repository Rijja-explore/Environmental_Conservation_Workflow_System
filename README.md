# 🌿 EcoGuardian Dashboard

## 📖 Description

**EcoGuardian** is a centralized dashboard built with Streamlit and Firebase to manage environmental conservation projects. It allows organizations or field teams to create, monitor, and approve projects, report incidents, and handle approval requests (e.g., funding, land access, permits). 

The system enables:
- Efficient **project lifecycle tracking**
- Real-time **incident reporting**
- Streamlined **approval management**
- Admin-level control to approve or reject requests

It serves as a lightweight and scalable solution for eco-project oversight and resource allocation.

---

## 🚀 Features

- 🧾 Create and manage eco-projects with location & priority
- 🚨 Log and track environmental incidents like poaching or pollution
- 📝 Submit and monitor approval requests (e.g., permits, budget)
- 🔐 Admin dashboard to manage and process approvals
- 🧹 Auto-delete old approvals to keep database clean

---

## 🛠️ Tech Stack

- **Frontend & UI:** Streamlit
- **Backend:** Firebase Firestore (via `firebase-admin`)
- **Language:** Python
- **Libraries Used:**
  - `streamlit`
  - `pandas`
  - `firebase-admin`
  - `uuid`
  - `datetime`

---
## 📸 Screenshots
<img width="1919" height="871" alt="image" src="https://github.com/user-attachments/assets/1cac419e-02ee-4e6e-bdb7-5f37b5bcc790" />
<img width="1908" height="861" alt="image" src="https://github.com/user-attachments/assets/0dc17a42-c267-43cc-95f5-2b10fb465591" />
<img width="1916" height="863" alt="image" src="https://github.com/user-attachments/assets/76e69112-a0f7-4785-9273-2f59de4d360c" />



## Requirements

```bash
pip install streamlit pandas firebase-admin
```

▶️ Run the App
In the project root directory:

```bash
streamlit run main.py
```
