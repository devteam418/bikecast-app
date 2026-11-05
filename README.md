# BikeCast website

Marketing and support site for BikeCast, built with MkDocs in English and French.

Pages are in `docs/`: `page.md` is English and `page.fr.md` is French. Pushing to `main` publishes the site with GitHub Actions.

To preview it locally:

```sh
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/mkdocs serve
```
