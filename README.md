[README.md](https://github.com/user-attachments/files/34279889/README.md)
# EmployAI - AI-Powered Academia-Industry Skill Mapping & Placement Platform

EmployAI is an intelligent fullstack platform connecting students, academic institutions, and industry recruiters with AI-driven resume auditing, skill gap analytics, dynamic roadmaps, and automated role matching.

---

## ⚡ Quick Start (Permanent One-Command Setup)

You can run the entire platform (both Python FastAPI Backend and React Frontend) with a single command from this root directory:

### Option 1: Using npm (Recommended)
```bash
npm run dev
```
*(or `npm start`)*

### Option 2: 1-Click Windows Launcher
Double-click **`start.bat`** or run:
```powershell
.\start.ps1
```

---

## 🌐 Endpoints & Ports

| Service | Local URL | Description |
| :--- | :--- | :--- |
| **Frontend Web App** | `http://localhost:5173` | React 19 + Three.js Hologram UI |
| **Backend API** | `http://127.0.0.1:8000/api/v1` | FastAPI REST Endpoints |
| **Swagger Interactive Docs** | `http://127.0.0.1:8000/docs` | Interactive API documentation |
| **Health Check** | `http://127.0.0.1:8000/health` | Backend status verification |

---

## 🛠️ Running Services Individually

If you prefer running the backend and frontend in separate terminals:

### 1. Backend Server (Terminal 1)
```bash
cd backend
python run.py
```

### 2. Frontend Dev Server (Terminal 2)
```bash
cd frontend
npm run dev
```
