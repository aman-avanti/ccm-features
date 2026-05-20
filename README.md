# CCM Feature Map

Cash Collection & Reconciliation — feature map with hover-revealed PRD details.

**Live:** https://aman-avanti.github.io/ccm-features/

## Layout

A single static page (`index.html`) renders a grid of CCM features grouped by row, each colour-coded by status:

- Done
- In Progress
- Design
- Pending
- New

Hover any box to surface its PRD summary.

## Local preview

Open `index.html` directly in a browser, or serve the directory:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Updating

The page is generated from a source flowchart (`ccm_prd_flowchart_v*.html`). To publish a new version:

```sh
cp ~/Downloads/ccm_prd_flowchart_vN.html index.html
git add index.html
git commit -m "Update CCM feature map - vN"
git push
```

GitHub Pages picks up the change on `main` within a minute or two.
