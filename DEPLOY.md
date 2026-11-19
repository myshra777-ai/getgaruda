# Deploy getgaruda.in (GitHub Pages)

1. On GitHub create a new PUBLIC repo `myshra777-ai/getgaruda` (empty).
2. Put these files at the repo root (index.html, img/, .nojekyll) and push:
   git init && git add . && git commit -m "Add Garuda website" && git branch -M main
   git remote add origin https://github.com/myshra777-ai/getgaruda.git && git push -u origin main
3. Repo Settings > Pages > Source: "Deploy from a branch", branch main, folder / (root). Save.
   Site goes live at https://myshra777-ai.github.io/getgaruda/ within a few minutes.

## After GoDaddy activates the domain (KYC approved)
In GoDaddy DNS:
- Delete the "A  @  Parked" record.
- Add 4 A records, name @ : 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- Edit the CNAME "www" so it points to myshra777-ai.github.io (not getgaruda.in.)
- Do NOT touch the mail records (MX, SPF, DKIM, SRV, DMARC).
Then in GitHub Pages settings set Custom domain = getgaruda.in, wait for the DNS check, tick "Enforce HTTPS".
(Verify the four IPs on GitHub's current Pages docs before pasting.)

## Before you share it
- The "Ask about a pilot" button uses myshra777@gmail.com. Change it to rohit@getgaruda.in once that mailbox works (search index.html for mailto).
- Keep the page honest: add a feature or claim only after it ships.
