# Updating the getgaruda site

    cd ~/getgaruda
    rm -rf img index.html DEPLOY.md
    unzip -o ~/Downloads/getgaruda-site-v3.zip
    git add -A
    git commit -m "Website v3: contact, services, direct installs, agents, guides"
    git push

GitHub Pages republishes in 1 to 3 minutes. Hard-refresh (Ctrl+Shift+R).

## One setting you may want to change
Booking: create a free Cal.com or Calendly link, then in index.html find
    var CALL_URL = '';
and paste the link between the quotes. Every "Book a call" button will open it.
Until then, "Book a call" opens the request form and email to rohit@getgaruda.in.

## When getgaruda.in is active (after the .IN KYC)
GoDaddy DNS: delete "A @ Parked"; add four A records for @ pointing to GitHub Pages
(185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; check GitHub's
Pages docs first); set CNAME "www" to myshra777-ai.github.io. Leave mail records alone.
Repo Settings > Pages: Custom domain = getgaruda.in, then tick Enforce HTTPS.
Result: https://getgaruda.in and https://www.getgaruda.in both work.
