# SmartAcademy — Smart Curriculum Activity & Attendance Platform

Problem ID: IH-01

Frontend-only hackathon prototype using HTML5, CSS3, Vanilla JavaScript and localStorage. Chart.js and QR libraries are used only through CDN for charts/QR functionality.

## Run in VS Code
1. Open this folder in VS Code.
2. Install the Live Server extension.
3. Right-click `index.html` → Open with Live Server.
4. No Node.js, npm or backend is required.

## Demo credentials
- Student: student@smartacademy.demo / smart123
- Teacher: teacher@smartacademy.demo / smart123
- Admin: admin@smartacademy.demo / smart123

## Demo flow
Teacher → QR Attendance → Generate QR → copy token → Student → Attendance Center → paste token → Verify → attendance/localStorage updates → teacher/admin analytics reflect the data.

## Prototype limitation
**This version is a hackathon frontend prototype. Production deployment requires a secure backend and database.**

LocalStorage authentication is demonstration-only and is not production security.

## Folder structure
All requested HTML, CSS and JS files are kept separate. Demo data is in `js/data.js`; storage operations are in `js/storage.js`; feature logic is split by module.

## Reports
CSV export is browser-generated. Print reports can be saved as PDF from the browser print dialog.
