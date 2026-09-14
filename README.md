# Dongwen Ou / Andre

A personal academic homepage, hosted on GitHub Pages. Existing Jekyll routes, collections, and source files are retained.

## Everyday edits

- Homepage text and links: `index.html`
- Colors, spacing, mobile layout: `assets/css/personal.css`
- Profile photo: `images/andre-mountains.jpg` (user-provided IMG_1896 2.JPG)
- CV: currently under construction in `_pages/cv.md`; the outdated PDF has been removed.
- Notes: add a Markdown file to `_posts/`, with `title`, `date`, and `layout: personal` in its front matter. Do not set `sample: true` on your own writing.
- Shared layout for notes and CV: `_layouts/personal.html`

Original template posts are marked `sample: true` and omitted from the notes index. Their source files and existing URLs remain. The empty original 2012 file is also retained.

## Preview and publishing

The homepage is plain HTML. The CV, notes, redirects and older routes require Jekyll. Run `bundle install`, then `bundle exec jekyll serve` for the complete site. GitHub Pages uses the existing Jekyll setup; keep the existing publishing settings.

This revision was previewed locally. It has not been pushed to GitHub. A full Jekyll build must be verified before publishing.

## Credits

Original AcademicPages / Minimal Mistakes assets retain their existing MIT license in `LICENSE`. The new personal homepage and stylesheet replace the homepage presentation while retaining the original repository structure.
