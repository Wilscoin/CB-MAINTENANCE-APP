MAINTENANCE — BLUE EDITION

Included:
- Blue responsive interface for phone and desktop browsers
- Login screen; first use creates the first Administrator account
- Administrator can add member accounts and assign roles: Administrator, Maintenance Engineer, Workshop Supervisor, Mechanic, Storekeeper, Viewer
- Fleet register and service intervals (machines: 250 hours; trucks: 5,000 km)
- Maintenance jobs, oil consumption chart, stock/parts, daily checklist
- CSV exports and JSON backup/restore
- PWA manifest and offline shell

START:
1. Extract the ZIP.
2. Open index.html in a modern browser for a local demo.
3. On first open, create an Administrator username and password. Then sign in.
4. Use Members to create accounts for your team.

IMPORTANT SECURITY / SHARING LIMITS:
This is a local-first starter version. User accounts and app records are stored in the current browser/device only. Passwords are hashed in the browser, but this is NOT a substitute for secure server-side authentication. The member roles are not a secure access-control boundary against someone who can inspect or alter browser data. Users on other phones/computers will not share accounts or records. For production company use, connect hosted authentication and a shared database with server-side role permissions, backups, and audit logs.

PWA installation and offline caching require hosting over HTTPS (or localhost); service workers do not work from ordinary file:// pages. On iPhone, open the HTTPS site in Safari, tap Share, then Add to Home Screen. On Android Chrome, use Install app/Add to Home screen.
