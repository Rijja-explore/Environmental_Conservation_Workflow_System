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

## Requirements

```bash
pip install streamlit pandas firebase-admin
```

▶️ Run the App
In the project root directory:

```bash
streamlit run main.py
```
