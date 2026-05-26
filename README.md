# Lab Homepage Template for GitHub Pages

This folder contains a static laboratory website template inspired by the structure of strong academic lab sites such as Stanford SVL.

## Included pages

- `index.html`: homepage with hero, featured research, news, team preview, publications, and recruiting callout
- `people.html`: members grouped by role
- `research.html`: research themes and representative projects
- `publications.html`: publication list grouped by year
- `join.html`: recruiting and application information
- `contact.html`: address, email, and map placeholder
- `assets/styles.css`: shared styling

## Why this works for `github.io`

- No build step
- No framework dependency
- Can be hosted directly by GitHub Pages
- Easy to edit with plain HTML and CSS

## How to publish

1. Create a GitHub repository.
2. If you want the site at the root domain, name it `YOUR_USERNAME.github.io`.
3. Upload all files from this folder to the repository root.
4. In GitHub, open `Settings -> Pages`.
5. Under `Build and deployment`, choose `Deploy from a branch`.
6. Select the branch you push to, usually `main`, and folder `/ (root)`.
7. Save, then wait for the site to publish.

For a project repository such as `lab-website`, the published URL is usually:

`https://YOUR_USERNAME.github.io/lab-website/`

## What to replace first

1. Lab name, subtitle, and contact email on every page
2. Homepage headline and mission text in `index.html`
3. Placeholder people in `people.html`
4. Research themes and project descriptions in `research.html`
5. Publications and links in `publications.html`
6. Recruiting details in `join.html`
7. Address and map details in `contact.html`

## Recommended assets to prepare

- One team photo
- Portraits for members
- Three to six project cover images
- A complete publication list with links
- School logo or lab mark if you have one

## Suggested next step

Once your real content is ready, the cleanest upgrade path is to keep this layout and later move the people, publications, and news into data files or a simple static-site generator. For a first version, this pure static setup is the fastest way to launch.
