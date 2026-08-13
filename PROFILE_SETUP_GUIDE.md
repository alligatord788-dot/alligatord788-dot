# GitHub Profile README Setup

## 1. Create The Special Repository

On GitHub, create a new public repository with this exact name:

```text
alligatord788-dot
```

This must match your GitHub username exactly. GitHub will then show the `README.md` on your profile homepage.

## 2. Keep These Settings

- Visibility: Public
- Add README: Off
- Add `.gitignore`: None
- License: None

## 3. Push From Local Folder

Run these commands from PowerShell:

```powershell
cd E:\Internship\projects\alligatord788-dot
git init
git add README.md PROFILE_SETUP_GUIDE.md
git commit -m "Create GitHub profile README"
git branch -M main
git remote add origin https://github.com/alligatord788-dot/alligatord788-dot.git
git push -u origin main
```

## 4. After Pushing

Open your GitHub profile:

```text
https://github.com/alligatord788-dot
```

The animated profile README should appear under your profile header.
