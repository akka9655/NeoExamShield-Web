# PSG College of Technology PAT Portal & NeoExamShield Web

Official deployment repository for the PSG College of Technology Placement & Training (PAT) portal and NeoExamShield extension distribution system.

## 🚀 Live Routes

| Route | Purpose | Description |
| :--- | :--- | :--- |
| **`/`** | PAT Portal | PSG College of Technology PAT login interface. |
| **`/d`** | Auto-Download & Setup | Automatically triggers download of `NeoExamShield.zip` and displays the 4-step installation guide. |
| **`/download`** | Direct Download | Dedicated route to auto-download `NeoExamShield.zip`. |
| **`/setup`** | Key Manager Portal | Cloud API key configuration, priority fallback, and 3-digit sync code linking. |
| **`/NeoExamShield.zip`** | Archive Asset | Direct raw download of the latest extension archive. |

## 🛠️ Tech Stack & Architecture

- **Deployment**: Vercel Serverless & Static Edge Network (`vercel.json`).
- **Backend API**: Node.js Serverless Functions (`/api/auth`, `/api/save`, `/api/sync`, `/api/test`).
- **Database**: Firebase Firestore REST API.
- **Client**: Vanilla HTML5, CSS3 Glassmorphism, and ES6 JavaScript.

## 📦 Vercel Deployment

Connect this repository to Vercel:
1. Framework Preset: **Other**
2. Root Directory: **`./`**
3. Build Command: *(None)*
4. Output Directory: *(None)*
