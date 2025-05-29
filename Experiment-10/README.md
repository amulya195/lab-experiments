# Experiment 10 – Git History Queries

## a. Show Last 5 Commits:
\`bash
git log --oneline -n 5
\`

## b. List commits by author "JohnDoe" between 2023-01-01 and 2023-12-31:
\`bash
git log --author="JohnDoe" --since="2023-01-01" --until="2023-12-31" --pretty=format:"%h - %ad - %s" --date=short
\`

These commands help analyze recent project activity and filter commits by time and author.


