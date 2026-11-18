TECHPRODUCTION — SUPABASE PLAYER ACCOUNT SETUP

Files to upload to the ROOT of your GitHub repository:
- index.html (replace the existing file)
- supabase-config.js (new file)
- manifest.webmanifest (keep the existing file)
- sw.js (keep the existing file)

1. In Supabase, open Project Settings > API Keys (or the Connect dialog).
2. Copy the Project URL and the Publishable key. Do not use a secret key or service_role key.
3. In GitHub, open the TechProduction repository.
4. Click Add file > Upload files.
5. Upload index.html and supabase-config.js from this package. Choose to replace index.html if GitHub asks.
6. Commit the changes to the main branch.
7. Open supabase-config.js in GitHub, click the pencil/Edit button, and replace:
   PASTE_YOUR_PROJECT_URL_HERE
   PASTE_YOUR_PUBLISHABLE_KEY_HERE
   with your own Project URL and publishable key. Keep the single quotes. Commit the change.
8. Wait for GitHub Pages to publish, then open https://cpsmith75.github.io/TechProduction/ and refresh.
9. Test registration with an email address you control. If email confirmation is enabled, open the confirmation email before signing in.

SECURITY NOTES
- Never put the database password, Supabase secret key, or service_role key in website files.
- The publishable key is designed for public client use; database access must be protected by Row Level Security.
- This setup only creates accounts and reads the player's profile. Demo games/coins are not real rewards or cash balances.
