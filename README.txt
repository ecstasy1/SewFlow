SEWFLOW — PHONE-FIRST SEWING PRODUCTIVITY APP (STARTER)

Files:
- index.html: the working app (HTML structure, CSS design, and JavaScript behaviour are together for easy first steps)

Features:
- Today dashboard: outstanding jobs, overdue jobs, due tasks, urgent jobs
- Add/edit/delete sewing jobs with customer, outfit, deadline, status, price, amount paid, balance, and notes
- Status stages: Not started, Cutting, Sewing, Finishing, Fitting, Ready for pickup, Delivered
- Search and filter jobs
- Add tasks, priority, deadline, mark complete, delete
- 15/25/45-minute focus timer
- Progress counters
- Export and restore a JSON backup
- Saves data in browser local storage

IMPORTANT DATA LIMITATION:
This starter stores records only in the browser on the current device. It does not sync to another phone or cloud. If browser data is cleared or the phone is lost, records may be lost. Use Progress > Export backup regularly. Before relying on it for important business records, we should add secure cloud storage and account access.

HOW TO PREVIEW:
Open index.html in a browser. For a phone installable version, we need to host it over HTTPS and add the PWA manifest/service worker in the next step. This first version is intentionally a single file so a beginner can inspect it easily.

NEXT STEPS:
1. Test adding 3 real jobs and 3 tasks.
2. Check that deadlines, statuses, and balances display correctly.
3. Turn this into a proper installable Android PWA with offline shell.
4. Add secure cloud backup/sync before depending on it as the only business record.
