# 🚚 Project Synapse: AI-Powered Last-Mile Delivery Platform (Vengers Delivery App)

### 🧠 Overview
*Project Synapse (Vengers Delivery App)* is an *AI-powered last-mile delivery platform* that streamlines parcel delivery operations through intelligent automation.  
It provides a dual-interface system for *customers* and *riders*, enabling seamless booking, dispatch, tracking, and delivery — all within a single platform.  

Built as a *full-stack application, it integrates **FastAPI, **SQLModel, **TailwindCSS, and **LLMs (Large Language Models)* to deliver optimized routes, real-time tracking, and automated customer support.

---

### 💡 Key Features
- 🧭 *Dual Dashboard System* — Separate dashboards for customers and riders  
- 🧠 *AI Integration (LLM)* — Smart address verification and optimized delivery route planning  
- 🌍 *Real-Time Tracking* — Implemented using *Leaflet.js* for dynamic delivery visualization  
- 💬 *AI Chatbot* — Provides customer support and automated issue resolution  
- ⚡ *FastAPI Backend* — Built complete REST APIs with efficient database integration using SQLModel  
- 🗂 *Database Management* — Handles orders, users, routes, and transaction data securely  
- 🎨 *Responsive UI* — Developed with TailwindCSS for sleek and adaptive design  
- ☁ *Cloud Deployable* — Designed for easy hosting and scaling on cloud environments  

---

### 🧰 Tech Stack
| Component | Technology Used |
|------------|------------------|
| *Frontend* | HTML, CSS, JavaScript, TailwindCSS |
| *Backend* | Python, FastAPI |
| *Database* | SQLModel / PostgreSQL |
| *AI/ML* | LLM Integration (for address verification & chatbot) |
| *Mapping* | Leaflet.js (for real-time route visualization) |
| *Hosting* | AWS / Render / Railway |
| *Version Control* | Git & GitHub |

---

### ⚙ Installation & Setup

Follow these steps to set up and run the project locally:

bash
# Clone this repository
git clone https://github.com/Jainadarsh101805/Project-Synapse.git

# Move into the project folder
cd Project-Synapse

# Backend setup
cd Backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend setup
cd frontend
npm install
npm start
---

## 🧠 **System Workflow**

1. User logs in as **Customer** or **Rider**
2. Corresponding dashboard loads with role-specific UI
3. Address input triggers AI verification logic
4. VengerBot helps navigate and resolve issues
5. Users track delivery status visually

---

## 🧪 **Challenges Solved**

### ✔ **Responsive Layout Issues**

Early UI broke on smaller screens → Fixed using Tailwind’s `sm:`, `md:`, `lg:` utilities.

### ✔ **Cluttered Delivery Information**

Replaced long forms with step-by-step cards & timelines.

### ✔ **Chat UI Overlapping**

Solved using scroll containers and component restructuring.

### ✔ **Slow API Loading States**

Implemented loading skeletons + fallback UI.

---

## 📘 **What I Learned**

* Designing production-style dashboards
* Real-world UI architecture
* Clean component structuring & semantic HTML
* Problem-solving with UX-first approach
* Using TailwindCSS for scalable styling
* Creating assistant-like chatbot UI flows

---


## 📄 **License**

MIT License © 2025 Akarsh Jain

---

## 🙌 **Author**

**Akarsh Jain**
Frontend Developer | AI-Enhanced UI Designer | Java Developer 

* LinkedIn: *(https://www.linkedin.com/in/akarsh-jain-940220252/)*
