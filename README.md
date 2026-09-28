# PULSE@UNSW — Learning Made Visible

**PULSE@UNSW** is a research-group website for **Personalised Understanding of Learning & Student Experience**.

> Learning Made Visible

## Website pages
- Home
- News
- Team
- Publications
- Research
- Projects
- Resources

## Repository structure
- `assets/images/branding/` — logos and brand graphics
- `assets/images/team/` — member photos
- `assets/images/projects/` — project imagery
- `assets/images/research/` — research graphics
- `assets/images/news/` — news/event imagery
- `publications/YYYY/` — distributable publication files/supplements
- `resources/datasets/` — datasets
- `resources/tools/` — software/tools
- `resources/teaching/` — teaching resources
- `resources/templates/` — templates
- `projects/` — project-related files
- `docs/` — website maintenance notes

## Publish with GitHub Pages — browser method
1. Sign in to GitHub and create a new repository. A name such as `pulse-unsw` works well. If you want the root URL `YOUR-USERNAME.github.io`, the repository must have that exact name.
2. Extract this ZIP on your computer.
3. In the new GitHub repository, choose **Add file → Upload files**.
4. Upload the *contents* of the `pulse-unsw` folder, preserving the folders. `index.html` must be at the repository root.
5. Commit the files.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch **main**, folder **/(root)**, then Save.
9. After GitHub finishes deployment, use the URL shown in the Pages settings.

For a normal project repository named `pulse-unsw`, the URL is typically:
`https://YOUR-USERNAME.github.io/pulse-unsw/`

## Publish from Terminal
After creating an empty GitHub repository:

```bash
cd pulse-unsw
git init
git add .
git commit -m "Initial PULSE@UNSW website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/pulse-unsw.git
git push -u origin main
```

Then enable GitHub Pages in **Settings → Pages → Deploy from a branch → main → /(root)**.

## Editing
The site intentionally uses plain HTML/CSS/JS so it can be maintained without a build system. Replace starter content in each `.html` page and add images/files to the matching folders.

## Important
Only upload publication PDFs, images, datasets and other resources that PULSE@UNSW has permission to distribute. Follow UNSW requirements for official branding and logos.
