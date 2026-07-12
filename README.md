# Tristan Vappi / Lobster Website

A static, GitHub Pages-ready artist website with:

- Home page
- Goals page
- Services page
- SoundCloud profile and featured-track links
- SoundCloud embed for "Avalon"
- Contact email links
- Temporary payment buttons routed to the Wikipedia page for doughnuts

## Preview locally

Open `index.html` directly, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this package.
3. Open the repository's **Settings**.
4. Select **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder.
7. Save and wait for GitHub to publish the site.

## Replace the temporary payment link

Search the project for:

```text
https://en.wikipedia.org/wiki/Doughnut
```

Replace it with Tristan's final payment URL.

## Main editable content

- `index.html`: Home-page copy, featured track, contact links
- `goals.html`: Goals and creative direction
- `services.html`: Service descriptions and booking buttons
- `styles.css`: Colors, layout, spacing, and animations
- `script.js`: Mobile navigation and scroll-in animations
