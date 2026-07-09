BouMatic Digital Portal — Deployment Package
=============================================

FILES:
  index.html           — Portal home page (start here)
  cs-skill-coverage.html — CS Skill & Coverage app
  hrms.html            — Company HRMS
  project-mgmt.html    — Project Management
  gmop.html            — GMOP Marketing Platform
  field-service.html   — Field Service Time Registration

DEPLOY:
  Option A — GitHub Pages (recommended)
    1. Create a new GitHub repo (e.g. boumatic-portal)
    2. Upload all files to the root
    3. Settings → Pages → Deploy from main branch
    4. Share the URL with your team

  Option B — Netlify Drop
    1. Go to netlify.com/drop
    2. Drag the entire folder
    3. Done — live in seconds

LOGIN:
  Every app uses username + PIN.
  Full credentials list is on the portal home page (index.html).
  Admin login: arsalan.m / 100001
  HR Admin:    admin / 999999

NOTES:
  - Data is stored in memory per session (refreshing resets)
  - For persistent data: connect to SharePoint Lists (guide available)
  - Microsoft SSO can replace PIN login when IT is ready

Built by: Arsalan M., BouMatic Automation Team, 2026
