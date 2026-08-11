EXOTIC SURAJ CYBER CAFE

IMPORTANT FOR YOUTUBE:
Do not double-click index.html and expect every YouTube video to play.
YouTube's embedded player needs a real web origin.

BEST:
1. Deploy this folder to Vercel/Netlify/GitHub Pages.
2. Open the deployed https:// address.
3. Open JUKEBOX.
4. Paste a normal YouTube video or public playlist URL.
5. Press SAVE & PLAY.

LOCAL TEST:
Run a local server from this folder, for example:
  python -m http.server 8000
Then open:
  http://localhost:8000

If YouTube returns error 101 or 150, that specific video has embedding disabled.
That restriction cannot be bypassed by JavaScript. Use another video or OPEN IN YOUTUBE.

If it returns 153 while opened with file://, use localhost or the deployed HTTPS site.
