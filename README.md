# ahmet-kurt.github.io

Personal academic website of **Ahmet Kurt, Ph.D.**

I'm a Tenure-Track Assistant Professor in the Department of Computer Science and Information Systems at East Texas A&M University (RELLIS campus). I work at the intersection of blockchains and their cybersecurity applications, and most of my research revolves around Bitcoin and the Lightning Network.

**Live site:** https://ahmet-kurt.github.io

Built with [Jekyll](https://jekyllrb.com/) using the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template.

## Local preview

Requires Docker.

```bash
docker compose up -d      # serve at http://localhost:4000
docker compose restart    # apply changes made to _config.yml
docker compose down       # stop
```

Edit a file and refresh the browser. Most content lives in:

- `_news/`: news items (one Markdown file each; newest shows first automatically)
- `_pages/`: the pages (about, publications, teaching, cv, contact)
- `_data/publications.yml`: the publication list
