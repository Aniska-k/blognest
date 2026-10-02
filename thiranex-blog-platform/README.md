# Thiranex Blog Platform

Full working full-stack blog platform using Express + JSON-file persistence (no native database build tools required).

## Features
- Register/login/logout with JWT
- Create, edit and delete your own posts
- Comments with edit/delete ownership checks
- Search posts
- REST API + health endpoint
- Responsive frontend
- Persistent local data in `data/db.json`

## Windows setup
1. Install Node.js LTS/current.
2. Open PowerShell in this folder.
3. Run `npm.cmd install` (use `npm.cmd` if PowerShell blocks `npm.ps1`).
4. Run `npm.cmd start`.
5. Open http://localhost:3000

No Visual Studio or C++ build tools are required.

## API health
http://localhost:3000/api/health
