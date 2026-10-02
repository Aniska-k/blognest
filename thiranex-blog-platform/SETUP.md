# Quick Setup — Windows

### 1. Open PowerShell
Go to the extracted folder:

```powershell
cd C:\Users\Admin\Downloads\thiranex-blog-platform
```

### 2. Install dependencies
```powershell
npm install
```

### 3. Start the full-stack website
```powershell
npm start
```

### 4. Open the website
```text
http://localhost:3000
```

### Important
Do not use Live Server for this project. The Express server serves the frontend and API together.

If port 3000 is busy, create `.env` from `.env.example` and set another port, for example `PORT=3001`.
