# CuriousBrief

A standalone editorial website for original, research-backed explainers inspired by public questions and discussion trends.

## Current setup
- Static, responsive website (no paid hosting required).
- Article index is read from `posts.json`.
- Each published article has its own URL and SEO metadata.
- No Quora answer or user content is copied. Public questions are topic signals only; articles must be independently researched and written.

## Local preview
Open `index.html` with a local static server (for example, VS Code Live Server).

## Publishing an article
Add the article HTML under `articles/<slug>/index.html` and add its metadata to `posts.json`. Keep article URLs canonical and include title, description, date, category, and reading time.

## Important limitation
Quora does not provide a generally available official API for reliably extracting all trending questions. Automated discovery must use permitted public access and may be incomplete or blocked. Do not bypass login, CAPTCHA, rate limits, or access controls. If public discovery is unavailable, use manually supplied public question URLs or an approved search source.