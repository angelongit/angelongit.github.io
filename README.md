# angelongit.github.io

Portfolio site for Angel Lopez. Plain HTML and CSS, no build step.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page: intro, projects, skills, background, contact |
| `spot.html` | Spot project page |
| `vaultlink.html` | VaultLink project page |
| `assets/style.css` | One stylesheet for every page |
| `assets/img/` | Images |
| `Angel_Lopez_Resume.pdf` | Resume linked from the Resume buttons |

## Publishing

Put these files at the top level of a public repository named `angelongit.github.io`, then in the repository's Settings, under Pages, set the source to the `main` branch. The site appears at https://angelongit.github.io.

## Common updates

- **New resume:** replace `Angel_Lopez_Resume.pdf`, keeping the file name.
- **Project photo:** save it in `assets/img/` and change the `src` of the image in the project's section of `index.html` or on its page.
- **Demo video:** each project page has a commented-out `<video>` block near the top. Save the clip in `assets/video/`, then remove the comment markers.
- **VaultLink status:** edit the Status section at the bottom of `vaultlink.html`, and the status tags near the top of that page and on its entry in `index.html`.
