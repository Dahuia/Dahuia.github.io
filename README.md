# Hui Zhu — Personal Website

A no-build static site, ready for GitHub Pages.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a repository named `Dahuia.github.io`.
2. Copy the contents of this folder to that repository.
3. Push to the default branch and enable Pages from the repository settings if needed.

## Personalize before publishing

- Replace `assets/Hui_Zhu_CV.pdf` whenever your CV changes.

## Regenerate the CV

The editable source is `cv/Hui_Zhu_CV.html`. After editing it, regenerate the downloadable PDF with:

```bash
libreoffice --headless --convert-to pdf --outdir assets cv/Hui_Zhu_CV.html
```
