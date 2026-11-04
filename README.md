# Tarun Singh — Academic Website

This package contains the refined personal academic website.

## Files
- `index.html` — responsive single-page academic website
- `profile.jpg` — profile photograph
- `cv.pdf` — downloadable academic CV

## Publish with GitHub Pages
1. Download and extract this ZIP.
2. Open the repository: https://github.com/Tarunsinghce97/Tarunsinghce97.github.io
3. Replace the corresponding files in the repository root (`index.html`, `profile.jpg`, and `cv.pdf`).
4. Commit the changes to the `main` branch.
5. Wait for GitHub Pages to rebuild, then check https://tarunsinghce97.github.io/.

The package is prepared locally; the live GitHub Pages site is not changed until these files are committed to the repository.

## Content notes
The research section distinguishes published contributions from ongoing directions. Conference presentations remain separate from journal publications. The Non-linear Mechanics Laboratory is linked as the research group; the personal site retains its own identity and content.


## Conference photo gallery

The website now includes a responsive Conference Gallery with photographs from:
- IUTAM Symposium 2026, IIT Delhi
- IMPLAST 2025, IIT Roorkee
- INCAM 2026, IIT Kanpur

Gallery photographs are stored in `images/gallery/`. To add another photograph:
1. Copy the image into `images/gallery/`.
2. Add another `<figure class="gallery-card">...</figure>` inside the `.gallery-grid` in `index.html`.
3. Update the image path, descriptive `alt` text, title, event details and lightbox caption.
4. Commit and push the updated files to the GitHub Pages repository.

The gallery images open in an enlarged lightbox; press Escape or click the close icon to return.


## Lab dinner photographs

Five lab-dinner photographs have been added under the **Lab dinners** subsection of the Gallery. They are stored in `images/gallery/` as `lab-dinner-01.jpeg` through `lab-dinner-05.jpeg`. The existing conference photographs and lightbox behaviour are retained.

No event date or venue has been assigned because those details were not provided. To add more photographs, copy them into `images/gallery/` and add matching `<figure class="gallery-card">...</figure>` entries in the Lab &amp; group moments grid in `index.html`.


## Gallery photographs

The Gallery section includes conference presentations, lab dinners, and moments in the research laboratory. Photograph files are stored in `images/gallery/`.

To add more photographs:
1. Copy the image into `images/gallery/`.
2. Add a matching `<figure class="gallery-card">...</figure>` entry in the relevant `.gallery-grid` inside `index.html`.
3. Use the image path in both the button's `data-full` attribute and the image's `src` attribute.
4. Write a concise, accurate `alt` description and caption. Avoid adding dates or event names unless they are known.
5. Commit and push the updated files to the GitHub Pages repository.


### Newly added INCAM photographs
Two additional photographs from the 7th Indian Conference on Applied Mechanics (INCAM 2026), IIT Kanpur (9–11 July 2026), are stored in `images/gallery/`:
- `incam-2026-portrait-01.jpeg`
- `incam-2026-portrait-02.jpeg`

The photos are displayed in the conference gallery and open in the existing lightbox when selected.


### Website layout update
The photo gallery and its navigation link have been removed from this version of the website.
