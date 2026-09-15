# Sazzad Yousuf Sourab's portfolio

A static research portfolio for Mohammed Sazzad Yousuf Sourab, Graduate Research Assistant at Lamar University. It includes publications, current research, selected projects, teaching experience, and professional links.

The site uses HTML, CSS, and a small JavaScript file. There is no installation or build step. The portrait, styling, and CV are included locally.

## Publish on GitHub Pages

1. Sign in to the **Sazzad8311** GitHub account and create a public repository named **sazzad8311.github.io**. If that repository already exists, update its website files instead.
2. Extract the downloaded ZIP. Upload the files **inside** the extracted folder to the repository. `index.html` must be at the top level, beside `styles.css`, `script.js`, and the `assets` folder. Do not upload the ZIP itself.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**. Choose **main** and **/(root)**, then **Save**.
5. Once publishing finishes, use **Visit site** in the Pages settings. The intended address is [sazzad8311.github.io](https://sazzad8311.github.io/).

GitHub says publication can take up to 10 minutes after a push. See its [site creation guide](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) and [publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

All local links are relative, so the portfolio also works in a project repository. In that case the address is your account's GitHub Pages address followed by the repository name.

## Open it on your computer

Extract the whole ZIP, then open `index.html` in a browser. Keep the `assets` folder beside it.

For a local web server, run this optional command inside the extracted folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Make updates

| What to change | Where to edit |
| --- | --- |
| Name, biography, dates, email, or profile URLs | `index.html` |
| Research descriptions and publication status | The labeled research and publications sections in `index.html` |
| LinkedIn post links and teaching experience | The experience section in `index.html` |
| Colors and fonts | The `:root` variables at the top of `styles.css` |
| Portrait | Replace `assets/portrait.jpg` and update its alt text if needed |
| CV | Replace `assets/Resume_Mohammed_Sazzad_Yousuf_Sourab.pdf` using the same filename |
| Mobile navigation behavior | `script.js` |

The page's content is present in the HTML. It does not depend on a JavaScript fetch, a framework, or an external font service. Professional profile and publication links open the relevant external websites.

## Content notes

- The M.S. completion date is **May 2027**, following the CV supplied for this website. The date appears in the education section.
- The IEEE QCE26 paper is labeled **accepted**. SC26 is labeled **poster accepted**. TACCSTER is labeled **upcoming**. The ICECE manuscript is **under review**. Update these labels as their status changes.
- The downloadable CV is the original supplied file. Updating the webpage does not update the PDF automatically.
- Source links and attribution are recorded in `SOURCES.md`.
- The contact link opens the visitor's email application. There is no contact form, account system, or analytics service.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Complete portfolio content and metadata |
| `styles.css` | Responsive layout, colors, typography, and print styling |
| `script.js` | Mobile menu, active navigation, and copyright year |
| `assets/portrait.jpg` | Portrait from the owner's public LinkedIn profile |
| `assets/Resume_Mohammed_Sazzad_Yousuf_Sourab.pdf` | Downloadable CV |
| `404.html` | Missing-page message |
| `.nojekyll` | Tells GitHub Pages to serve the static files directly |
| `SOURCES.md` | Content sources and portrait attribution |

## Validation

The delivered package was checked for missing local assets, broken internal anchors, duplicate element IDs, and JavaScript syntax. No browser-based layout or interaction test was performed in this environment.

This package is ready for your upload. It has not been published to GitHub.
