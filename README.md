# HoopTracker

A responsive, dark silver basketball performance tracker.

## Features
- Shot tracking by 9 court positions with automatic FG%
- Game log: points, rebounds, assists, steals, blocks
- Monthly training calendar, workout completion and notes
- Progress overview and development goal
- Water and nutrition habit check-ins
- Local browser storage and installable PWA shell

## Run locally
Open `index.html` in a browser, or use a local static server.

## Publish on GitHub Pages
1. Create a public GitHub repository named `hooptracker`.
2. Upload all files from this folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Wait for the deployment URL shown in Pages.

## Publish on Netlify
1. Open Netlify and choose **Add new site → Deploy manually**.
2. Drag the entire `HoopTracker` folder (or its ZIP contents) into the deploy area.
3. Netlify will publish the static site and provide a URL.

## Important
This first version stores data in the current browser using `localStorage`. It does not sync between devices and browser data can be lost if site data is cleared. Scheduled push notifications and cloud accounts are not included yet.
