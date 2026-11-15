# SLV Fashion Store

Static store (index.html + images folder). Orders go to Supabase so the admin sees every order live.

## Put it online with GitHub Pages
1. Create a new repository on github.com (Public).
2. Click "uploading an existing file" and drag in index.html and the images folder contents. Commit.
3. Settings > Pages > Source: "Deploy from a branch" > Branch: main, folder: / (root) > Save.
4. Your site opens at https://YOUR-USERNAME.github.io/REPO-NAME/
5. Admin: add #admin to the address, or tap the footer SLV logo 5 times.

## Before real orders work
Open index.html and paste your Supabase URL and anon key into the SETTINGS lines at the top of the script.
Follow SETUP.txt (Supabase steps) first. The anon key is safe to be public. Never upload the service_role key.
