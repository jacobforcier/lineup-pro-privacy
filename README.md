# Lineup Pro – Privacy Policy

This repo hosts the privacy policy for the **Lineup Pro** iOS app on GitHub Pages.

**Live URL:** https://jacobforcier.github.io/lineup-pro-privacy

---

## How to publish (one-time setup)

1. Go to https://github.com/new
2. Create a new repository named exactly: `lineup-pro-privacy`
   - Set visibility to **Public**
   - Do NOT initialize with a README (you'll push this folder)

3. In Terminal, run:
   ```bash
   cd ~/Desktop/lineup-pro-privacy
   git init
   git add .
   git commit -m "Add privacy policy"
   git branch -M main
   git remote add origin https://github.com/jacobforcier/lineup-pro-privacy.git
   git push -u origin main
   ```

4. In your GitHub repo, go to **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Click **Save**

5. Wait ~60 seconds, then visit:
   **https://jacobforcier.github.io/lineup-pro-privacy**

6. Paste that URL into:
   - App Store Connect → App Information → Privacy Policy URL
   - The `Link` in SettingsView.swift (already set)

---

## Updating the policy

Edit `index.html`, then:
```bash
git add index.html
git commit -m "Update privacy policy"
git push
```

Changes go live in ~60 seconds.
