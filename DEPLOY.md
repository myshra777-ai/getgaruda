# Garuda website v4

## Publish
    cd ~/getgaruda
    git pull
    rm -rf img index.html DEPLOY.md
    unzip -o ~/Downloads/getgaruda-site-v4.zip
    git add -A && git commit -m "Website v4: shorter page, FAQ, comparison, book a demo"
    git push

Keep the CNAME file. The commands above don't touch it.

## Fill in later (index.html, near the top of the <script> block)
- CALL_URL = 'https://cal.com/...'   your booking link (Cal.com or Google Calendar)
- WHATSAPP = '91XXXXXXXXXX'          WhatsApp business number, digits only, with country code
Until CALL_URL is set, "Book a demo" opens an email to contact@getgaruda.in. "Ask us" opens your LinkedIn profile until WHATSAPP is set.
