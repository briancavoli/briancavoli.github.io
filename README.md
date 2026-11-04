# briancavoli.github.io

Personal executive website for Brian Cavoli, hosted on GitHub Pages. Plain HTML and one stylesheet: no build step, framework or CMS.

## Structure

| Page | File |
|---|---|
| Home | `index.html` |
| Experience & Results | `experience/index.html` |
| Marketing Leadership | `leadership/index.html` |
| Tribute Home Care case study | `experience/tribute-home-care/index.html` |
| dunnhumby & BzzAgent case study | `experience/dunnhumby-bzzagent/index.html` |
| Growth Systems | `growth-systems/index.html` |
| Perspectives | `perspectives/index.html` |
| Building the Next Generation of Home Care | `perspectives/next-generation-home-care/index.html` |
| Connect | `connect/index.html` |
| Opportunity page template (unlisted) | `for/template/index.html` |
| Not found | `404.html` |

Shared assets live in `assets/` (`css/site.css`, self-hosted font, images, favicon, social share image).
The old `.html` pages (`experience.html`, `growth-systems.html`, `marketing.html`, the five system pages, and `my-story/`) are kept as redirects so existing links keep working.

## Editing

- **Copy:** edit the text directly in the page's `index.html`.
- **Styles:** colors, fonts and spacing are tokens at the top of `assets/css/site.css`.
- **Header and footer:** repeated in each page. If you change navigation, change it in every `index.html` (an AI assistant can do this in one pass).
- **New pages:** add them to `sitemap.xml`.

## Adding a personalized opportunity page

1. Copy `for/template/` to `for/<organization-slug>/`.
2. Replace every `[BRACKETED]` placeholder; delete sections you don't need.
3. Keep the `noindex` tag. Don't link to it from other pages; share the URL directly.
4. Unlisted is not private: never include confidential information.
