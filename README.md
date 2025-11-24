📦 StreamInterakt Assets

This repository hosts all public static images used by the StreamInterakt application.
These files are served through GitHub Pages and used inside the app to keep the client build lightweight and fast.

⸻

🎯 Purpose
	•	Centralize icons and images for the StreamInterakt dashboard
	•	Reduce application bundle size
	•	Provide a simple CDN-like URL structure
	•	Allow easy updates to assets without shipping a new app build

⸻

📁 Repository Structure

/  
├── games/  
│   ├── league-of-legends.png  
│   ├── apex-legends.png  
│   ├── valorant.png  
│   └── ...  
├── index.html  
└── README.md  

	•	/games → logos or images representing each supported game
	•	index.html → minimal entry page for GitHub Pages
	•	README.md → this file

⸻

🌐 Accessing Assets (CDN Links)

All files are publicly accessible via GitHub Pages.

Base URL:  
https://HeavyLab.github.io/streaminterakt-assets/

Example image URLs:  
https://HeavyLab.github.io/streaminterakt-assets/games/league-of-legends.png
https://HeavyLab.github.io/streaminterakt-assets/games/apex-legends.png

⸻

🔄 Updating Assets

	1.	Replace or upload the file in the correct folder
	2.	Commit & push
	3.	GitHub Pages updates automatically within seconds
	
If you need to force-refresh an asset in the app, append a version tag:

.../league-of-legends.png?v=2

⸻

🛠️ Adding New Assets

	•	Use lowercase file names
	•	Avoid spaces → use - or _
	•	Prefer .png or .webp for UI consistency
	•	Keep file sizes small (recommended < 500 KB)

Example naming convention:

games/<game-id>.png
