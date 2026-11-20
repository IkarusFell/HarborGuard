HARBOR GUARD

Built by Team NullTrace for Crimeathon 2026 (SIMATS Engineering, Chennai) Case: CR-26-047 · Harbor & Finch Freight

A security dashboard prototype that protects a freight company from fake bank-detail changes, misused API keys, bulk data exports, leaked credentials and slow incident response.

The problem

Attackers changed vendor bank details, abused API keys, exported data in bulk and found credentials pasted into support tickets, while the response was slow.

Our solution
Module	What it does
Financial protection	Blocks bank changes that have no approval reference
Credential manager	Scores key risk; rotate, restrict to IPs, or revoke
API monitoring	Flags suspicious requests and bulk exports; one-click block
Data exposure	Scans tickets for leaked keys and shows them masked
Moderation	Holds risky content, redacts it, or escalates it to an incident
Incidents and audit trail	Status, owner, timeline, reports and a full action log
Threat level	Live 0-100 score on the dashboard
Roles

Admin, Analyst, Auditor and Viewer. The Viewer sees only the summary. The login locks for 30 seconds after 3 wrong passwords.

Project structure
harbor-guard/
├── index.html   # page structure
├── style.css    # theme and fonts
├── app.js       # all app logic and views
└── README.md
Run it

Open index.html in a browser, or use VS Code with the Live Server extension. An internet connection is needed for the React, Tailwind and font libraries.

Live demo: https://YOUR-USERNAME.github.io/harbor-guard/

Notes
All data is simulated and nothing connects to real systems.
The demo password is checked in the browser and is for demonstration only.
Team NullTrace

Designed and coded by Team NullTrace for Crimeathon 2026.
