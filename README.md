# How to update the website
1. Edit index.md
1. Convert to HTML: `pandoc -s index.md -o index.html -c css/style.css`
1. Insert noindex meta tag in `<head>`: `<meta name="robots" content="noindex">`
1. Commit and push (or pull request)