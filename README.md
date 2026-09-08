# DATA100 Course Website

A Quarto website template for DATA100: Introduction to Data Analytics.

## Setup
1. Open this folder as an RStudio Project (or `quarto preview` from the terminal).
2. Update `_quarto.yml`: site-url, GitHub repo link.
3. Add your rendered slide decks to `slides/`.
4. Update `schedule.qmd` with real term dates.
5. Fill in real assignment due dates in `assignments.qmd`.

## Preview locally
    quarto preview

## Publish to GitHub Pages
    git init
    git add .
    git commit -m "Initial course site"
    git remote add origin https://github.com/yourusername/data100-course.git
    git push -u origin main
Then enable GitHub Pages in repo Settings, pointing at the `_site` folder or a `gh-pages` branch,
or use `quarto publish gh-pages` to automate this.
