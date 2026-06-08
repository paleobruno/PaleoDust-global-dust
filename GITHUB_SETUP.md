# GitHub setup notes

## Option A: Upload from the GitHub website

1. Create a new repository on GitHub.
2. Suggested repository name: `PaleoDust-global-dust`.
3. Keep it public if you want it visible on your profile.
4. Upload the full contents of this folder.
5. Pin the repository from your GitHub profile so it appears at the top.

## Option B: Upload from the terminal

```bash
cd PaleoDust-global-dust
git init
git add .
git commit -m "Initial PaleoDust analysis repository"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/PaleoDust-global-dust.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

## GitHub profile README

If you want a personal profile README, create a separate repository with exactly the same name as your GitHub username. That README is different from this project repository.
