MICHELLE LEVESQUE — SELECTED WORK

DEFAULT PASSWORD
helloThere!!

WHAT IS INCLUDED
- index.html — password-protected portfolio page
- links.js — add your Google Drive / PDF URLs here
- assets/ — logo and Team Alignment Sprint image
- downloads/ — Learning Experience Design + Learning Modality decks
- rise/ — two Leadership Snacks courses, each with its own password gate

HOW TO DEPLOY ON GITHUB PAGES
1. Upload the CONTENTS of this folder to a GitHub repository.
2. Settings → Pages → Deploy from a branch → main / root.
3. Your page will be at https://USERNAME.github.io/REPOSITORY/

HOW TO ADD YOUR GOOGLE DRIVE LINKS
Open links.js and replace each # with the share URL for that sample.
Use view-only links.

PASSWORD SECURITY NOTE
This uses a client-side SHA-256 password gate. It is appropriate for sanitized portfolio samples, but it is not strong access control for confidential/proprietary material because static-site files can still be discovered by a determined technical user. For true access control, put the site behind Cloudflare Access, Netlify password protection, or another server-side/authentication layer.

HOW TO CHANGE THE PASSWORD
The current password is: makingworkwork
To change it, generate a SHA-256 hash for your new password and replace PASSWORD_HASH in index.html and the HASH constant in each Rise course index.html. If you send me the new password, I can regenerate the package for you.
