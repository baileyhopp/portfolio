# Bailey Hopp | Social Media Portfolio

A static portfolio site for Bailey Hopp, social media manager, built for GitHub Pages. It uses plain HTML and CSS with no build step and no dependencies.

Live site: https://baileyhopp.github.io/portfolio/

## What is inside

| Path | Purpose |
| --- | --- |
| `index.html` | Home page: intro, results, featured work, tools |
| `assets/style.css` | Shared styles, with automatic light and dark mode |
| `work/social-posts.html` | Social media post series sample |
| `work/case-study.html` | Customer case study sample |
| `work/blog-post.html` | Thought leadership article sample |
| `work/product-messaging.html` | Product marketing sample |
| `work/whitepaper.html` | Whitepaper executive summary and outline sample |

## Important: samples are placeholders

Every company, customer, quote and statistic in `work/` and in the Results and Tools sections of `index.html` is a fictional placeholder. Replace them with real work, or remove any piece that cannot be backed up, before sharing the site widely.

## Folder structure matters

The pages expect this exact layout, so keep the folders when uploading:

```
index.html
assets/style.css
work/*.html
```

If the pages look unstyled or links are broken, a file is probably in the wrong folder.

## Publish on GitHub Pages

1. Put the files in the repository `baileyhopp/portfolio` on the `main` branch, keeping the folders above.
2. Open **Settings > Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
3. After a minute or two the site is live at https://baileyhopp.github.io/portfolio/.

## Customize

- To change text, open a file on GitHub, click the pencil icon, edit the words between the HTML tags, and commit.
- Edit colors at the top of `assets/style.css` (the `:root` block).
- To add a project, copy a file in `work/`, edit it, and add a matching block to the featured work section in `index.html`.
