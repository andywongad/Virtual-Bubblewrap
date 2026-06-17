DROP AUDIO FILES HERE
─────────────────────────────────────────────────
Supported formats: mp3, wav, ogg, m4a

Special filenames the app looks for automatically:

  pop.mp3        → replaces the synthesised bubble-pop sound
  fresh.mp3      → plays when Fresh Sheet is clicked

Any other filename can be played by calling:
  playAsset('audio/your-file.mp3')
from the browser console, or wired into the code.

Tips
────
• Keep pop sounds short (< 200ms) for best feel in Manic Mode.
• Files must be in the same folder as index.html when hosted
  (Netlify / GitHub Pages / Neocities all serve public/ correctly).
• On a local file:// URL, audio loading works fine in Chrome/Edge;
  Safari may block it — use a local server (e.g. VS Code Live Server).
