# naomishimberg.github.io

Personal website, served by GitHub Pages at https://naomishimberg.github.io.

- `index.html` is the whole site: research, policy work, and media.
- `_includes/about.html` is the bio under the photo.
- `_layouts/default.html` holds the left column: photo, name, contact, bio, and the CV link.
- `assets/css/style.css` sets the layout, the green link color, and the font (Open Sans, loaded from Google Fonts).
- PDFs go in `files/`.
- The browser-tab icon (a lightning bolt) is `images/favicon.svg`, with PNG copies `favicon-32.png` and `apple-touch-icon.png` for older browsers and phone home screens.

To add a paper, copy an existing `<div class="paper">` block in `index.html` and edit it (the comment at the top of that file explains the parts). The title is green whether or not it links anywhere. Link the paper from its title. The row underneath takes any of Abstract, Slides and Media, which open drop-downs. Leave out the ones a paper doesn't have.
