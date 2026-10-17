KRISHNA'S BIRTHDAY WEBSITE
==========================

FILES
- index.html
- photos/memory-1.jpeg ... photos/memory-6.jpeg

IMPORTANT: Keep the photos folder and index.html together. The website references photos using relative paths.

MIDNIGHT TIMER
The countdown uses the visitor's device local time and unlocks at the next 12:00 AM.
For the intended surprise, publish this site before midnight and send her the URL.
Note: This is a client-side reveal, not security. Anyone who inspects the page source can bypass it. It is intended as a fun birthday reveal, not for protecting confidential content.

PUBLISH WITH GITHUB PAGES
1. Create a PUBLIC repository on GitHub, e.g. birthday-surprise.
2. Upload index.html and the entire photos folder (all six JPEGs).
3. Open repository Settings > Pages.
4. Under Build and deployment, select Deploy from a branch.
5. Choose branch main and folder /(root), then Save.
6. Wait for deployment. Open the URL shown in Pages, typically:
   https://YOUR-USERNAME.github.io/birthday-surprise/
7. Test on a phone using mobile data/incognito before sending the link.

Do not rename or separate the photos unless you also update their paths in index.html.

HOMEPAGE COUPLE PHOTO
- The homepage also uses photos/couple-home.jpeg. Upload this file along with the six memory photos in the photos folder.

INDIA-TIME REVEAL
The birthday reveal is set to October 18, 2026 at 12:00 AM India Standard Time (IST, UTC+05:30). The same instant is used for all visitors regardless of their device timezone. If changing the birthday date, update the ISO timestamp in index.html.
