# Sales Summary — Bootstrap SPA for GitHub Pages

Summary
- A small single-page application that loads a CSV of sales data embedded as a data URI (attachment) and computes the total sales.
- It sets the page title to 'Sales Summary SEED-001' and displays the computed total in an element with id #total-sales.
- Bootstrap 5 is loaded from jsDelivr for styling.

Features
- Fetch data.csv attachment via data URI
- Parse and sum the sales column
- Dynamic document title using seed value
- Bootstrap 5 styling from jsDelivr

Setup (GitHub Pages)
1. Create a repository on GitHub (e.g., yourname/sales-summary).
2. Add the three files in the repo: index.html, README.md, LICENSE.
3. Commit and push to GitHub.
4. In the repository settings, under Pages, select the source as the main branch (root) and save. The site will be published at https://yourusername.github.io/repo-name/.

Usage
- Open the site URL. You should see the total sales displayed and the title 'Sales Summary SEED-001'.

Code overview
- index.html: Main page. Loads Bootstrap, defines the UI, and contains a small script that reads the embedded CSV data URI, sums the sales, and updates the DOM. It also sets window.seed and the document title.
- No external API calls required; the CSV data is embedded for a fully offline-ready static site.

Files
- index.html
- LICENSE
- README.md

License
MIT license text is included in the LICENSE file. This project uses the MIT license standard terms.
