# 🚀 Build Chrome-Themed Overlayed on GitHub (EASY MODE)

## What This Does

GitHub will build the installers for you automatically in the cloud - you just download them when done!

---

## 📋 Step-by-Step Instructions

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to https://github.com/signup
2. Enter your email and create a password
3. Verify your email
4. **Done!** (Free account is fine)

---

### Step 2: Create a New Repository

1. Go to https://github.com/new
2. **Repository name:** `overlayed-chrome-theme`
3. **Description:** `Chrome-themed Overlayed Discord overlay`
4. **Make it Public** (so GitHub Actions are free)
5. **DON'T** check "Add a README"
6. Click **"Create repository"**

---

### Step 3: Upload the Code

**Option A: Use GitHub Website (Easiest)**

1. On your new empty repo page, look for **"uploading an existing file"**
2. Extract `overlayed-chrome-themed.zip` on your computer
3. Drag ALL the files from the extracted folder into GitHub
4. Wait for upload (might take 2-3 minutes)
5. Scroll down and click **"Commit changes"**

**Option B: Use Git (If you know how)**

```bash
# Extract the zip first
cd overlayed-0.6.2
git init
git add .
git commit -m "Chrome themed Overlayed"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/overlayed-chrome-theme.git
git push -u origin main
```

---

### Step 4: Enable GitHub Actions

1. Go to your repo on GitHub
2. Click the **"Actions"** tab at the top
3. Click **"I understand my workflows, go ahead and enable them"**
4. You'll see "Build Chrome-Themed Overlayed" - click it
5. Click **"Run workflow"** on the right
6. Click the green **"Run workflow"** button

---

### Step 5: Wait for the Build

1. The build will start automatically
2. You'll see three builds running:
   - 🪟 **Windows** (builds .msi installer)
   - 🍎 **macOS** (builds .dmg installer)
   - 🐧 **Linux** (builds .deb and .AppImage)

3. **Wait 20-40 minutes** (GitHub is compiling everything)
   - Windows: ~30 minutes
   - macOS: ~35 minutes
   - Linux: ~25 minutes

4. When done, you'll see **green checkmarks** ✅

---

### Step 6: Download Your Installers

1. Click on the completed workflow run
2. Scroll down to **"Artifacts"**
3. Download what you need:
   - **overlayed-chrome-windows.zip** (for Windows)
   - **overlayed-chrome-macos.zip** (for Mac)
   - **overlayed-chrome-linux.zip** (for Linux)

4. Extract the zip
5. **Install the app!** 🎉

---

## 🎨 What You Get

✅ Windows `.msi` installer  
✅ macOS `.dmg` installer  
✅ Linux `.deb` and `.AppImage`  
✅ All with chrome theme built-in!  
✅ Ready to share with friends!  

---

## 🐛 Troubleshooting

**"Actions" tab doesn't appear**
- Make sure the repository is **Public**
- Refresh the page

**Build failed with red X**
- Click the failed build to see error
- Usually means a dependency issue
- Try clicking "Re-run all jobs"

**Upload is taking forever**
- Be patient, GitHub can be slow
- Make sure your internet is stable
- The zip is ~15-20MB, might take a few minutes

**Can't find the .github folder when uploading**
- Make sure "Show hidden files" is enabled
- On Windows: View → Show → Hidden items
- On Mac: Cmd+Shift+. in Finder

---

## ⏱️ How Long Does This Take?

- **Creating GitHub account:** 5 minutes
- **Uploading code:** 5 minutes
- **Setting up Actions:** 2 minutes
- **Waiting for build:** 30-40 minutes (GitHub does the work!)
- **Downloading:** 2 minutes

**Total time YOU spend:** ~15 minutes  
**Total time WAITING:** ~30-40 minutes  

---

## 💡 Pro Tips

- You can close the browser while it builds
- GitHub will keep building in the background
- Come back in 30-40 minutes to download
- The installers will be saved for 90 days
- You can share your repo link with friends so they can download too!

---

## 📱 What Operating System Are You On?

Let me know which installer you need and I can give you more specific instructions for installing it once it's downloaded!

- Windows: Double-click the `.msi` file
- Mac: Open the `.dmg` and drag to Applications
- Linux: `sudo dpkg -i overlayed-chrome*.deb` or run the `.AppImage`

---

## 🎉 After Installation

1. Open Overlayed
2. Join a Discord voice channel
3. **Watch the chrome effects!** ✨
   - Ripples when talking
   - Glowing rings
   - Chains when muted
   - All your requested effects!

---

**Need help with any step? Just ask!** 🚀
