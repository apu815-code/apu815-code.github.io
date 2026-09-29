# Mahbub Alam: personal website (al-folio + GitHub Pages)

## 1. Publish (about 10 minutes)
1. On GitHub, create a **public** repository named exactly `<your-username>.github.io`.
2. Upload everything in this folder to it (drag and drop in the browser, or `git push`).
   Make sure the hidden `.github` folder is included.
3. Edit `_config.yml`: replace `YOUR-GITHUB-USERNAME` in `url:` with your username (line ~23).
4. In the repo, open **Settings → Pages** and set **Source = Deploy from a branch**, **Branch = gh-pages / (root)**.
   (The first push runs the *Deploy site* action, which creates the `gh-pages` branch. Wait ~3 minutes for it.)
5. Your site is live at `https://<your-username>.github.io`.

## 2. Own domain (optional)
Buy a domain, add a file named `CNAME` at the repo root containing just the domain, set the DNS records GitHub lists
(Settings → Pages → Custom domain), tick *Enforce HTTPS*, and change `url:` in `_config.yml` to the domain.

## 3. Things to fill in
| What | Where |
|---|---|
| Real photo (600×750 px) | replace `assets/img/prof_pic.jpg` |
| ORCID / LinkedIn / GitHub | `_data/socials.yml` (uncomment lines) and `_data/cv.yml` |
| Papers from 2024 onward (TIFET, borophene, Bi2Te3 etc.) | `_bibliography/papers.bib`. Paste BibTeX from Google Scholar |
| Student list | `_pages/people.md` (check names and add photos if you like) |
| CV | edit `_data/cv.yml`; the PDF rebuilds automatically |
| News items | add a file in `_news/` |
| Colours | top of `_sass/_themes.scss` (`--accent-1` … `--accent-4`) |

## 4. Adding an applet
See `assets/applets/README.md`. In short: put the HTML file in `assets/applets/<name>/`, copy `_applets/barrier-tunneling.md`, edit the title and path, and push.

## Notes
- Nothing was built locally in the authoring environment (its network could not reach the Ruby gem servers), so the first GitHub build is the first full test. If the Actions tab shows a red X, open the log and send it to me.
- `_sass/_themes.scss` replaces the theme's own colour file. After upgrading al-folio, run `bundle exec al-folio upgrade overrides audit`.
- Consultancy page lists clients by name (as requested) but no case details. Review it before publishing.
