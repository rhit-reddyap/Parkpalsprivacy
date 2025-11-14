# Instructions to Push to GitHub

## Step 1: Create the GitHub Repository

1. Go to https://github.com/new
2. Repository name: `parkpalsprivacy`
3. Description: "Privacy Policy for ParkPals mobile app"
4. Choose **Public** or **Private** (your choice)
5. **DO NOT** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

## Step 2: Push to GitHub

Run these commands in the `parkpalsprivacy` directory:

```bash
cd C:\Users\reddyap\Desktop\park-pals-mvp\parkpalsprivacy
git remote add origin https://github.com/YOUR_USERNAME/parkpalsprivacy.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

## Alternative: Using SSH

If you prefer SSH:

```bash
git remote add origin git@github.com:YOUR_USERNAME/parkpalsprivacy.git
git branch -M main
git push -u origin main
```

## What's Included

- `PRIVACY_POLICY.md` - Complete privacy policy document
- `README.md` - Repository description and information

