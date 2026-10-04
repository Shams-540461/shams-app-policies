# Shams app policies
Static HTML pages prepared for GitHub Pages. Not deployed yet.

## Review
- SSS Mobile App and SSS Arena wording and effective dates are preserved from the owner-provided policies. Migration is not a new audit of those apps.
- SSS Arena email is preserved as support@shamswmailik.com. Owner confirmation is needed: other apps use support@shamswmalik.com. Correct it before publishing if it is a typo.
- PDF Editor policy reflects the supplied backend, current no-ad version, and confirmed Render Hobby workspace in Oregon. No 90-day support-email deletion promise is made. Hosting infrastructure records and forwarded/exported logs are not covered by the seven-day dashboard-log figure. Update the policy if additional logging or processing is configured.
- This bundle does not change application code or add an in-app privacy link. Add the public policy link in each app as needed.

## Publish
1. Create a public repository named shams-app-policies under Shams-540461.
2. Extract the ZIP. Upload all files INSIDE this folder to the repository root. Do not upload the ZIP itself or nest the site in another folder.
3. Commit files to main.
4. Repository Settings > Pages: Deploy from a branch; main; / (root); Save.
5. Wait for the Pages deployment. Open each URL signed out and verify it loads.

Expected URLs AFTER successful deployment:
https://shams-540461.github.io/shams-app-policies/sss-mobile-app.html
https://shams-540461.github.io/shams-app-policies/sss-arena.html
https://shams-540461.github.io/shams-app-policies/shams-pdf-editor.html

Update Play Console and in-app links only after verification. Keep existing Shopify pages available for older installed app versions; do not remove them as part of initial migration.
