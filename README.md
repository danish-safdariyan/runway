# Runway

A private money planner that installs like an app, works offline, and keeps everything encrypted on your device.

## Put it online once (GitHub Pages)
1. Create a new public repository on GitHub, for example runway.
2. Upload every file in this folder to the repository root.
3. Settings, then Pages. Source: Deploy from a branch. Branch: main, folder: / (root). Save.
4. After a minute your app is at https://YOUR_USERNAME.github.io/runway/

The repository only holds app code. Your numbers never leave your device, and the app's security policy blocks it from contacting any other server.

## Install
iPhone: open the link in Safari, tap Share, then Add to Home Screen. Open Runway from the icon and create your passcode there.
Mac or PC: open the link in Chrome or Edge and click the install icon in the address bar. On Safari for Mac, use File, then Add to Dock.

Each installed copy has its own storage. Use Settings, then Save backup, and restore that file on your other device to copy your data over.

## Updating
Replace the files in the repository and change CACHE in sw.js (for example runway-v2). Installed apps pick up the new version next time they open online.
