GVP WATCH — DEMO PORTAL BUNDLE

Files:
- index.html: new landing page with links to all three portals
- admin.html: original GVP Smart Monitoring admin dashboard
- citizen.html: citizen issue reporting and complaint tracking
- cleaning-crew.html: cleaning task list and work update portal

GitHub Pages deployment:
1. Extract this ZIP file.
2. Open your existing GitHub repository.
3. Upload all four HTML files to the repository's root (same folder).
4. Keep index.html as the homepage. It is now the landing page.
5. The previous admin dashboard is available at /admin.html.
6. Enable GitHub Pages in Settings > Pages if it is not already enabled.

Demo limitations:
All three portals are front-end demonstrations using sample data. Their forms and status updates are not connected to one another, a shared database, live cameras, municipal staff or notification services. A production system needs a secure backend, authentication, role-based access and secure media storage.


SIGN-IN PROMPT
Clicking any portal card (or the control-room shortcut) opens a User ID and Password prompt before navigating to that portal. This is only a front-end demo gate: any non-empty ID/password will continue. It does NOT authenticate users, store accounts, or secure the portal files. For real login security, connect the portals to a backend authentication service and protect each portal route.
