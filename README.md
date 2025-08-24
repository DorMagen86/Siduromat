Siduromat — GitHub Actions Build Template
========================================
Push this repo to GitHub (no terminal needed). GitHub Actions will build:
- Windows: EXE (onefile) artifact
- macOS: .app + .dmg artifact

How to use:
1) Create a new empty GitHub repository in the GitHub web UI.
2) Click "Add file" → "Upload files" and upload everything from this folder.
3) Go to the "Actions" tab. The workflow "Build Siduromat" will start automatically.
4) When it finishes, open the run → "Artifacts" panel, and download the ready-made files:
   - Siduromat-Windows-EXE.zip  (inside: Siduromat.exe)
   - Siduromat-macOS-DMG.zip   (inside: Siduromat.dmg)

You can replace icons in /icons before uploading:
- app.ico (Windows), app.icns (macOS), app.png (Linux/general)
