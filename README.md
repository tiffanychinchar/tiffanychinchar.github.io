# Tiffany Chinchar — Sports Communications Portfolio

A static, responsive portfolio website for Tiffany Chinchar, designed for GitHub Pages.

## Publish to GitHub Pages (no coding required)

1. Sign in to GitHub as **tiffanychinchar**.
2. Create a **public** repository named exactly **tiffanychinchar.github.io** (do not add a README when creating it).
3. Click **Add file → Upload files** in the new repository.
4. Unzip the provided ZIP on your computer. Upload **the contents of the `tiffanychinchar-portfolio` folder** (the `index.html` file and the `css`, `js`, and `assets` folders), not the outer folder itself.
5. Click **Commit changes**.
6. In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save** (if not already configured).
7. Visit **https://tiffanychinchar.github.io/** after deployment finishes (typically a few minutes).

## Update the portfolio

- Edit `index.html` to change text, add cards, or update links.
- Add PDFs to `assets/documents/` and link to them from cards in `index.html`.
- Add images to `assets/images/` and reference their paths in HTML.
- Portfolio filter behavior lives in `js/main.js`. New cards should have `data-org="ucf"`, `data-org="bucs"`, or `data-org="orlando"` to work with the current filters. Update the filter counts in HTML when adding cards.
- Visual styles live in `css/style.css`.

## Included files

- `index.html` — complete single-page website
- `css/style.css` — responsive styling
- `js/main.js` — mobile navigation and project filters
- `assets/images/tiffany-field.jpeg` — homepage photograph
- `assets/documents/tiffany-chinchar-resume.pdf` — résumé
- `assets/documents/*.pdf` — three Buccaneers quote sheets converted from the supplied Word documents

## Attribution

UCF work and Buccaneers quote sheets are labeled as independently produced based on the portfolio owner's confirmation. The Orlando City match report is labeled collaborative. The unpublished men's tennis release is intentionally excluded.

## Notes

- Published article links point to the organizations' official sites and require an internet connection.
- The contact phone number and email are public on the website. Remove the phone link in `index.html` if you prefer not to display it publicly.
- This is a static website: no hosting subscription, database, or build system is required.
