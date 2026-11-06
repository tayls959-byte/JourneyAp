# Journey — private journal PWA

A mobile-friendly, installable daily journal with voice recording, local IndexedDB storage, searching, editing, audio playback, text sharing, and JSON backups.

## Publish with GitHub Pages
1. Upload all files **inside this folder** to the root of the `JourneyAp` repository (not the ZIP itself).
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. When deployment finishes, open `https://tayls959-byte.github.io/JourneyAp/` in Samsung Chrome and select **Add to Home screen** or **Install app**.

## Important privacy notes
- GitHub Pages hosts the *public application code*. Never upload your journal backup, private notes, or recordings to the repository.
- Journal entries and recordings stay on your device in browser IndexedDB. They are not automatically uploaded to ChatGPT or Google Drive.
- Browser data deletion or device loss can erase entries. Export backups regularly and store them privately.
- The **Share text** button shares/copies text; it does not send audio automatically. You can separately save audio and attach it in ChatGPT.
- Automatic transcription, Drive sync, user accounts, and encrypted backups are **not included**.
- GitHub Pages requires a publicly accessible website for a free public repository; this does not publish the journal data stored locally.

## Local development
Serve the directory with any local HTTP server (for example `python -m http.server 8000`); microphone and service worker features generally require HTTPS or localhost.
