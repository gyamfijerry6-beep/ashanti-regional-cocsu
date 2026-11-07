ASHANTI REGIONAL COCSU WEB APP
==============================

WHAT THIS PACKAGE DOES
- Provides the COCSU community prototype as a mobile-friendly web app.
- Can be installed on supported phones after it is published on an HTTPS website.
- Caches the app shell for offline reopening after the first successful visit.
- Saves demo posts and entries in the browser/device local storage.

IMPORTANT LIMITATION
This is not yet a shared multi-user platform. Entries created on one phone do not automatically appear on another phone. Public member accounts, real-time chat, shared posts, admin permissions, push notifications and a central database require a secure backend and authentication.

HOW TO PUBLISH IT FOR YOUR GROUP (GitHub Pages)
1. Sign in to GitHub and create a new public repository, for example: ashanti-regional-cocsu.
2. Upload ALL files in this folder to the repository's root:
   index.html, manifest.webmanifest, sw.js, icon.svg, README.txt
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish the site. Open the HTTPS address shown in Settings > Pages.
7. Share that published address with COCSU members.
8. On Android Chrome, open the site menu and choose Install app or Add to Home screen.
   On iPhone Safari, use Share > Add to Home Screen.

BEFORE OFFICIAL LAUNCH
- Appoint authorised administrators and agree who may publish official notices.
- Add a privacy notice and moderation/reporting process.
- Use a secure backend (for example, Firebase or Supabase) for shared accounts, posts, events and chat.
- Do not collect sensitive personal information or publish members' photos without permission.
- Test the site with a small group before wider release.

The app can be previewed locally by opening index.html, but service-worker/offline installation
works only when served from localhost or a secure HTTPS website.
