# GMChess privacy policy

The privacy policy page for the GMChess Android app (`index.html`), hosted
with GitHub Pages. Its URL goes in Google Play Console, AdMob and the
consent message.

## Before publishing

Replace the placeholder contact email (it appears twice):

```bash
sed -i 's/YOUR_CONTACT_EMAIL/you@example.com/g' index.html
```

## Publish with GitHub Pages

1. Create a new **public** repository on GitHub, e.g. `gmchess-privacy`.
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Privacy policy"
   git branch -M main
   git remote add origin git@github.com:<your-username>/gmchess-privacy.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy
   from a branch**, branch `main`, folder `/ (root)`, **Save**.
4. After a minute the page is live at
   `https://<your-username>.github.io/gmchess-privacy/`.

Use that URL in:
- Google Play Console → App content → **Privacy policy**
- AdMob → Apps → GMChess → **App settings** (privacy policy URL, if shown)
- AdMob → Privacy & messaging → the consent message

## Keeping it accurate

Update the policy (and its "Last updated" date) when the app starts
collecting or sending anything new - for example a new ad network,
analytics, crash reporting or accounts.
