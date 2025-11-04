# 🎨 Chrome-Themed Overlayed - Ready to Build!

## What I Did

I added the complete chrome theme to Overlayed! The modifications are in:
- `apps/desktop/src/styles.css` - Added all chrome effects at the end

## 🚀 How to Build (Easy Mode)

### Prerequisites:
- Node.js 18+ (download from https://nodejs.org)
- Rust (install from https://rustup.rs)
- pnpm (install with: `npm install -g pnpm`)

### Build Steps:

1. **Extract the zip file** (overlayed-0.6.2.zip with chrome theme)

2. **Open Terminal/Command Prompt** in the extracted folder

3. **Install dependencies:**
   ```bash
   pnpm install
   ```

4. **Build the app:**
   
   **Windows:**
   ```bash
   cd apps/desktop
   pnpm tauri build
   ```
   
   **Mac:**
   ```bash
   cd apps/desktop
   pnpm tauri build
   ```
   
   **Linux:**
   ```bash
   cd apps/desktop
   pnpm tauri build
   ```

5. **Find your installer:**
   - **Windows**: `apps/desktop/src-tauri/target/release/bundle/msi/` or `.exe`
   - **Mac**: `apps/desktop/src-tauri/target/release/bundle/dmg/`
   - **Linux**: `apps/desktop/src-tauri/target/release/bundle/deb/` or `.AppImage`

6. **Install and enjoy!** 🎉

---

## ⚡ Quick Build (If you have everything installed)

```bash
# From the root of overlayed-0.6.2/
pnpm install
cd apps/desktop
pnpm tauri build
```

Done! Your installer will be in `src-tauri/target/release/bundle/`

---

## 🎨 What's New - Chrome Effects

Your build includes:

✅ **Chrome ripples** when talking (Discord blue color)
✅ **Rotating glow rings** around active speakers  
✅ **Shimmer particles** floating around avatars  
✅ **Frozen glass overlay** on muted users  
✅ **Chrome chains** effect for muted state  
✅ **Ambient chrome atmosphere** throughout  
✅ **Edge glow bars** and corner accents  
✅ **Smooth animations** and transitions  

All effects work automatically - just join a Discord voice channel!

---

## 🐛 Troubleshooting

**"pnpm: command not found"**
```bash
npm install -g pnpm
```

**"cargo: command not found"**
- Install Rust from https://rustup.rs

**"Build failed - missing dependencies"**
- **Windows**: Install Visual Studio Build Tools
- **Mac**: Install Xcode Command Line Tools (`xcode-select --install`)
- **Linux**: Install build essentials (`sudo apt install build-essential`)

**Build takes forever**
- First build takes 10-30 minutes (compiling Rust)
- Subsequent builds are much faster

**"Permission denied" on Mac**
```bash
chmod +x apps/desktop/src-tauri/target/release/overlayed
```

---

## 📝 Notes

- Build time: **15-30 minutes** (first time)
- The chrome theme is **fully integrated** - no external CSS needed
- Works on **Windows, Mac, and Linux**
- The installer is **standalone** - share it with friends!

---

## 🔄 Reverting Changes

If you want to go back to original Overlayed:
1. Download original from https://github.com/overlayeddev/overlayed
2. The chrome theme is only in `apps/desktop/src/styles.css`
3. Remove everything after line 109 in that file

---

## 💬 Need Help?

If the build fails:
1. Make sure you have Node.js 18+ (`node --version`)
2. Make sure you have Rust (`rustc --version`)
3. Make sure you have pnpm (`pnpm --version`)
4. Try `pnpm install --force` if dependencies fail
5. Check Tauri docs: https://tauri.app/start/

---

**Built with ❤️ - Enjoy your chrome-themed Discord overlay!**
