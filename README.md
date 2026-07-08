# Sweet Cheeks Ice Cream Bar — landing page

## Files
- `index.html` — page content
- `style.css` — styling (cherry pink hero, mint social pills, "admit one" signup ticket)

## What to customize
1. **Social links** — in `index.html`, replace the `href="#"` on each `.social-pill` link with your real Instagram, TikTok, and Facebook URLs.
2. **Copy** — swap the placeholder headline/subhead in the `.hero` section for your own voice.
3. **Email signup** — replace the `<form id="signup-form">` block with your Mailchimp embed code (Audience → Signup forms → Embedded forms → choose "Naked" format, it's easiest to restyle). Paste it in exactly where the current form sits — the surrounding `.ticket` styling will still apply.

## Publish to GitHub Pages
1. Push these files to a GitHub repo (root of the repo, not a subfolder).
2. In the repo: **Settings → Pages** → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
3. Your site goes live at `https://yourusername.github.io/repo-name/` within a minute or two.

## Point your Squarespace-purchased domain at it
1. Add a file named `CNAME` (no extension) to the repo root containing just your domain, e.g. `sweetcheeksicecream.com`.
2. In Squarespace's DNS settings for the domain, add:
   - **A records** for `@` pointing to:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - A **CNAME record** for `www` pointing to `yourusername.github.io`
3. Back in GitHub repo Settings → Pages, enter your custom domain and enable "Enforce HTTPS" once available.

DNS changes can take a few minutes to a few hours to fully propagate.
