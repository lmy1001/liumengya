# Mengya Liu — personal website

Static website for https://lmy1001.github.io/liumengya/.

## Preview

Run `python3 -m http.server 8765` in this directory, then open http://localhost:8765.
No build step or package installation is required.

## Update

Edit `index.html` for the biography, News, and publications. Edit `style.css` for the layout. Publication images are stored locally in `assets/`; their original sources are listed in `assets/SOURCES.md`.

The November 2026 update adds Zero-HLM, its CoRL 2026 Late Breaking Results presentation announcement, and the September 2026 Delta-0 contributor blog entry. Zero-HLM credits Dianyi Yang and Mengya Liu as co-first authors, Wei Liang, Baoxiong Jia, and Siyuan Huang as co-last authors, and Baoxiong Jia as project lead. It corrects One2Any's paper URL and replaces placeholder links throughout. Papers without a verified standalone project website use their official paper landing page. The shape completion repository currently contains only a release announcement, so it is not presented as released code.

## Publish

Push the updated files to the repository's `main` branch; retain the existing GitHub Pages configuration. If GitHub authentication is missing, run `gh auth login` and `gh auth setup-git` first.

## Verification

- Seven publication entries, each with a local preview image and real destination links.
- HTML nesting, unique IDs, internal anchors, local images, and placeholder-link checks passed.
- Responsive CSS includes desktop, tablet, and mobile layouts, visible keyboard focus, and reduced-motion support.
- Browser visual checks were unavailable because no browser was connected; inspect desktop and mobile appearance before deployment.
