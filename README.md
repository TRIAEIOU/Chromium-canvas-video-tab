# Chromium-canvas-video-tab
Chromium extension that injects "Open in new tab" links in Instructure's Canvas LMS.
- The extension is definitely not 100% but just made to meet my requirements: Canvas videos are typically either too small (and don't scale with the browser window) or you have to make them full screen which is less than helpful when on a large monitor, when opened in a new tab they will scale with the browser window.
- To install download files and "Load unpacked extension" from a chromium browser "Settings/Extensions".
- Edit manifest.json/content_scripts/matches to include any URLs your insititution may have that uses Canvas as backend for media files.
