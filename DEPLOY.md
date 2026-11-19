# Updating the getgaruda site

This folder replaces the first version in the getgaruda repo.

    cd ~/getgaruda
    rm -rf img index.html DEPLOY.md
    unzip -o ~/Downloads/getgaruda-site-v2.zip
    git add -A
    git commit -m "Website v2: dashboard styling, privacy, real output, install tabs"
    git push

GitHub Pages republishes in 1 to 3 minutes. Hard-refresh (Ctrl+Shift+R) to see it.

## Before you share it
- "Ask about a pilot" and "Tell us what you need" use myshra777@gmail.com.
  Search index.html for "mailto:" and change both to rohit@getgaruda.in once that mailbox works.
- The "guard on a real commit" tab shows your own Talon run from 19 Nov 2026 on Garuda's repo.
- Fonts load from Google Fonts. Everything else is in this folder.
- Add a claim only after the feature ships.

## When getgaruda.in is active (after the .IN KYC)
In GoDaddy DNS: delete "A @ Parked"; add A records for @ pointing to GitHub Pages
(185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; check GitHub's
Pages docs first); point CNAME "www" to myshra777-ai.github.io. Leave mail records alone.
Then in repo Settings > Pages set Custom domain = getgaruda.in and tick Enforce HTTPS.
