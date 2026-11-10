# Om Dhinoja · Engineering Projects

Static site, no build step. Upload this whole folder to a GitHub repo and turn on Pages.

## Structure
```
index.html                 Home: About, Projects, Contact
uv-led-fixture/            UV LED Optical Module Assembly Fixture (page, images, docs)
fire-fighter-robot/        Fire Fighter Robot (page, images, Arduino code)
```

## Publish on GitHub Pages
1. Create a repo. Name it `<your-username>.github.io` for the site to live at `https://<your-username>.github.io`.
2. Upload everything in this folder to the repo root (keep the folders).
3. Settings → Pages → "Deploy from a branch" → `main` / `(root)`.
4. Live in a minute or two.

## Adding a project
## Resume
Put your resume PDF in the top folder, next to index.html, named exactly `Om_Dhinoja_Resume.pdf`. To update it later, upload a new file with the same name.

## Adding a project (steps)
1. Make a new folder, e.g. `pothole-machine/`, with its `index.html` and `images/`. Copy an existing project page as the template so the theme stays the same.
2. In the new page, keep the `← All projects` link (`href="../#projects"`) and the logo link (`href="../"`).
3. In the home `index.html`, copy one `<li>...</li>` card block in the Projects list and change the folder, image, number, title, text and chips.
