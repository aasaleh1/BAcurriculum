# Bayaan Academy curriculum guides

Static site. Nine pages, each self-contained: HTML, styling and data in one file,
no build step and no server.

| File | What it is |
|---|---|
| `index.html` | Front page. Pick a grade, see all five subjects for the year. |
| `ela.html` | English Language Arts, K–12 |
| `ela-wall.html` | ELA benchmark wall |
| `ela-activities.html` | ELA activity bank |
| `math.html` | Mathematics, K–12 |
| `science.html` | Science, K–11 |
| `social-studies.html` | Social Studies, K–11 |
| `qais.html` | Qur'an, Arabic and Islamic Studies, K–12 |
| `404.html` | Shown on a bad link |
| `robots.txt` | Asks search engines not to index the site |

Standards: Florida B.E.S.T. for English and mathematics, NGSSS for science and
social studies, department plans for Qur'an, Tajweed, Arabic and Islamic Studies.

## Deploying

Any static host serves this as-is. Drag the folder onto app.netlify.com/drop, or
enable GitHub Pages under Settings with the branch root as the source.

## Editing

The guides are generated from one dataset. Edits made directly to a page are lost
at the next build, so corrections go to Aamena.
