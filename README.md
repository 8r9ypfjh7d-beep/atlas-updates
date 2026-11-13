# atlas-updates

Holds the update files for the Atlas iPhone app, served by GitHub Pages.

- `u/<version>.bin` is one update. Each file is encrypted (AES-256-GCM) with its own key, so it reads as noise here.
- The app runs an update only after its owner approves it on the phone with Face ID.
- Nothing else belongs in this repo. No code, no data, no keys.
