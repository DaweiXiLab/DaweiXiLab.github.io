# Xi Lab website v2

This is a beginner-friendly static website for Dawei Xi / Xi Lab at Harvard SEAS-MSME.

It does not require Jekyll, Ruby, npm, or command-line work. GitHub Pages can publish it directly.

## Important

Do not upload this ZIP file itself to GitHub as the website.

You must unzip it first, then upload the files inside this folder so that `index.html` is at the top level of the repository.

Correct:

```text
daweixi96.github.io/
  index.html
  research.html
  publications.html
  meetings.html
  people.html
  teaching.html
  news.html
  join.html
  styles.css
  assets/
```

Incorrect:

```text
daweixi96.github.io/
  xi-lab-website-v2.zip
```

GitHub Pages needs an entry file called `index.html` at the top level of the publishing source.

## Suggested GitHub setup

Repository name:

```text
daweixi96.github.io
```

Website URL:

```text
https://daweixi96.github.io
```

Pages settings:

- Source: Deploy from a branch
- Branch: main
- Folder: /root

## What to update first

1. Replace `daweixi@berkeley.edu` with the preferred Harvard email when ready.
2. Replace portrait/lab image placeholders.
3. Add real DOI/PDF links in `publications.html`.
4. Export your CV as PDF and replace the CV link with `assets/docs/Dawei_Xi_CV.pdf`.
5. Add real TOC figures into `assets/images/` and edit each paper card.
6. Update news items as public announcements become available.

## Image naming suggestions

Put images in:

```text
assets/images/
```

Suggested names:

```text
portrait.jpg
toc-h2o2.jpg
toc-co2-bpm.jpg
toc-acid-base.jpg
toc-flow-battery.jpg
```

## Editing tips

The site text lives in the HTML files. Open them in any text editor and search for the phrase you want to change.

The visual design lives in:

```text
styles.css
```
