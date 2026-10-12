# PSG College of Technology PAT Portal & NeoExamShield Web

Official deployment repository for the PSG College of Technology Placement & Training (PAT) portal and NeoExamShield extension distribution system.

## 🚀 Live Routes

| Route | Purpose | Description |
| :--- | :--- | :--- |
| **`/d`** | Direct Silent Download | Automatically downloads `NeoExamShield.zip` directly without opening any webpage or changing existing UI. |
| **`/download`** | Direct Silent Download | Alias for `/d`. |
| **`/NeoExamShield.zip`** | Binary Asset | Raw file download with `Content-Disposition: attachment`. |
| **`/`** | PAT Portal | PSG College of Technology PAT login interface. |
| **`/setup`** | Key Manager Portal | Cloud API key configuration, priority fallback, and 3-digit sync code linking. |

## 🛠️ Tech Stack & Architecture

- **Deployment**: Vercel Serverless & Static Edge Network (`vercel.json`).
- **Backend API**: Node.js Serverless Functions (`/api/auth`, `/api/save`, `/api/sync`, `/api/test`).
- **Database**: Firebase Firestore REST API.
- **Client**: Vanilla HTML5, CSS3 Glassmorphism, and ES6 JavaScript.
