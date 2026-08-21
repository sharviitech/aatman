# Aatman — static website

Plain HTML/CSS export. No build step, no server needed.

## Publish on GitHub Pages
1. Create a new GitHub repo (e.g. `aatman-site`), Public.
2. Upload ALL files in this folder to the repo root (index.html, about.html,
   services.html, contact.html, 404.html, styles.css, .nojekyll, assets/).
   In GitHub: "Add file" > "Upload files" > drag everything > Commit.
3. Repo > Settings > Pages > Source: "Deploy from a branch",
   Branch: `main`, Folder: `/ (root)` > Save.
4. Wait ~1 minute. Your link: https://<username>.github.io/<repo-name>/

Share that link with the client.

## Notes
- The contact form opens the visitor's email app (mailto: hello@aatman.example).
  Replace that address in contact.html (search for "mailto:") with the real one.
- To update the site later, re-upload the changed files.
