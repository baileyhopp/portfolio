# Bailey Hopp | Social Media Portfolio

A static portfolio site for Bailey Hopp, social media manager, built for GitHub Pages. It uses plain HTML and CSS with no build step and no dependencies.

Live site: https://baileyhopp.github.io/portfolio/

## What is inside

| Path | Purpose |
| --- | --- |
| `index.html` | Home page: intro, results, selected work, tools and background |
| `assets/style.css` | Shared styles, with automatic light and dark mode |
| `work/cbt-nuggets.html` | CBT Nuggets role page |
| `work/bamboo.html` | Bamboo role page |
| `work/within.html` | WITHIN role page |
| `work/wander-willamette.html` | IronGlove Studio / Wander Willamette page |
| `work/davies-dixon.html` | Davies + Dixon role page |
| `work/social-posts.html` | Placeholder for live post examples |

## Content status

Metrics and role details come from the 2026 resume and LinkedIn profile. The "Examples coming soon" notes and the `work/social-posts.html` page are placeholders for live posts, videos, and newsletter issues.

## Folder structure matters

The pages expect this exact layout, so keep the folders when uploading:

```
index.html
assets/style.css
work/*.html
```

## Publish on GitHub Pages

1. Put the files in the repository `baileyhopp/portfolio` on the `main` branch, keeping the folders above.
2. Open **Settings > Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
3. After a minute or two the site is live at https://baileyhopp.github.io/portfolio/.

## Customize

- To change text, open a file on GitHub, click the pencil icon, edit the words between the HTML tags, and commit.
- Edit colors at the top of `assets/style.css` (the `:root` block).
- To add a project, copy a file in `work/`, edit it, and add a matching block to the selected work section in `index.html`.
