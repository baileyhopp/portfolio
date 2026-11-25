# B2B Marketing Content Portfolio

A static portfolio site for B2B content marketing work, ready for GitHub Pages. It uses plain HTML and CSS with no build step and no dependencies.

## What is inside

| Path | Purpose |
| --- | --- |
| `index.html` | Home page: intro, work grid, about, contact |
| `assets/style.css` | Shared styles, with automatic light and dark mode |
| `work/product-messaging.html` | Product marketing sample |
| `work/case-study.html` | Customer case study sample |
| `work/whitepaper.html` | Whitepaper executive summary and outline |
| `work/blog-post.html` | Thought leadership article |
| `work/social-posts.html` | Social media post series |

## Important: samples are placeholders

Every company, customer, quote and statistic in `work/` is fictional. Replace them with your own work, or remove any piece you cannot back up, before sharing the site.

## Publish on GitHub Pages

1. Create a repository on GitHub. For a personal site named `your-username.github.io`, use that exact repository name.
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```
3. In the repository, open **Settings > Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. After a minute or two the site is live at `https://your-username.github.io`.

## Customize

- Search for `Your Name`, `you@example.com` and `your-username` and replace them.
- Edit colors at the top of `assets/style.css` (the `:root` block).
- To add a piece, copy any file in `work/`, edit it, and add a card to the grid in `index.html`.
- Use a custom domain by adding a `CNAME` file containing your domain.
