Equipment Data Tracker:
Full-stack CRUD app for managing equipment inventory (Machine, Vessel, Tank, Mixer) with search, filter, sort, and mobile-responsive UI.

-> Features
CRUD operations - Create, Read, Update, Delete
Search - Real-time search by name, type, status
Filters - Dropdown filters for Type & Status
Sorting - Clickable table headers (▲/▼)


-> Tech Stack
text
Frontend: React 18 + React Bootstrap 5
API: JSON Server (mock backend)
State: React Hooks (useState, useEffect, useMemo)
Deployment: GitHub Pages

-> Quick Start (2 Minutes)
Prerequisites
text
Node.js 18+ 
npm/yarn
Local Development (Full Backend)
bash
git clone https://github.com/Keerthikumargilky/equipment-data-tracker.git
cd equipment-data-tracker
npm install

Terminal 1 - Backend:
bash
npx json-server --watch db.json --port 3001

Terminal 2 - Frontend:
bash
npm start
App: http://localhost:3000

Live Demo 
https://keerthikumargilky.github.io/equipment-data-tracker

-> Equipment Types & Status
text
Types: Machine, Vessel, Tank, Mixer
Status: Active, Inactive, Under Maintenance

How to Use
Add: Fill form → Submit
Search: Type in search box
Filter: Use Type/Status dropdowns
Sort: Click table headers
Edit: Edit button → Modal
Delete: Delete → Confirm

Demo Data Structure:
json
{
  "items": [
    {
      "id": 1,
      "name": "Boiler-01",
      "Type": "Machine",
      "Status": "Active",
      "Action": "2025-12-01"
    }
  ]
}
