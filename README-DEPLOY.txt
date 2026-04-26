CDA Appliances — Deploy Instructions (Windows)

1) Extract this ZIP to a normal folder (NOT inside iCloud/OneDrive if possible).
   Example: C:\cda-site

2) Open Command Prompt and run:
   cd C:\cda-site
   firebase login
   firebase use cda-website-78020
   firebase deploy --only hosting

Notes:
- This package includes the correct folder structure for images used in index.html.
- If iCloud renames dotfiles (like .firebaserc), keep the versions in this ZIP.

2/10/2026 latest deploy text is C:\Users\FBS\OneDrive\Documents\01 website\cda-site-fixed-v4>
