# Dr. Mukesh Pandey — Personal Website

This repository contains a single-page personal/academic website (`index.html`) — no build step, no dependencies. It's ready to publish for free with GitHub Pages.

## Deploy in 5 minutes (GitHub Pages)

1. **Create a GitHub account** (skip if you have one): https://github.com/signup

2. **Create a new repository**
   - Click the **+** icon (top right) → **New repository**
   - Name it either:
     - `<your-username>.github.io` — this gives you the cleanest URL: `https://<your-username>.github.io`
     - or any other name, e.g. `personal-website` — this gives you: `https://<your-username>.github.io/personal-website`
   - Set it to **Public**
   - Click **Create repository**

3. **Upload your file**
   - On the new repo page, click **Add file → Upload files**
   - Drag in `index.html` (and `LICENSE` if you want it in the repo)
   - Click **Commit changes**

4. **Turn on GitHub Pages**
   - Go to **Settings → Pages** (left sidebar)
   - Under "Build and deployment," set **Source** to `Deploy from a branch`
   - Set **Branch** to `main` and folder to `/ (root)` → **Save**
   - Wait ~1 minute, then refresh — GitHub will show you the live URL at the top of that page

5. **Done.** Your site is now live and free, permanently, with no ads or hosting costs.

## Making updates later

Any time you want to edit the page (new publication, updated bio, etc.), either:
- Edit `index.html` directly on GitHub (click the pencil icon on the file) and commit, or
- Come back here and ask Claude to make the edit, then re-upload the file (drag-and-drop overwrite works fine).

## Custom domain (optional)

If you'd like `mukeshpandey.com` instead of the github.io address:
1. Buy a domain from any registrar (Namecheap, Google Domains successor Squarespace Domains, etc.)
2. In your repo, add a file named `CNAME` containing just your domain, e.g. `mukeshpandey.com`
3. In your domain registrar's DNS settings, add a CNAME record pointing to `<your-username>.github.io`
4. In GitHub → Settings → Pages, enter the custom domain and enable "Enforce HTTPS"

## License

This repository is licensed under the MIT License (see `LICENSE`) — meaning the code/template is free for anyone to reuse, but obviously the personal content (your name, bio, publications) is yours.
