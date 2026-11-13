# Jyoti Singh | BIM Architect

Personal portfolio website for Jyoti Singh, BIM Architect, hosted on GitHub Pages.

## Contents

- `index.html` - the whole site (HTML, CSS and JS inline, no build step).
- `assets/` - portrait, cover photo and project renders. Project drawings are deliberately not kept here; they stay in the Drive portfolio.
- `Jyoti_Singh_CV.pdf` - the résumé behind the "Download CV" buttons. Replace the file (same name) to update it.

## Updating content

- **Projects** are listed in the `WORKS` array near the bottom of `index.html`. Each entry has a title, location, description, tags and a list of images (`['file-name-without-.jpg', 'caption']`); the first image is the large one. Drop new JPGs into `assets/` and reference them there.

- **Demo videos and portfolio PDF** are embedded from the shared Google Drive folder by file ID:
  - videos: the `data-video="..."` attribute on each `.tool-media` block
  - portfolio: the `drive.google.com/file/d/<ID>/...` links in the Portfolio section

  If a file is re-uploaded to Drive it gets a new ID, so update the ID here. Files must be shared as "Anyone with the link".
- **Other text** (about, experience, skills) is plain HTML in `index.html`.

## Preview locally

Open `index.html` in any modern browser.
