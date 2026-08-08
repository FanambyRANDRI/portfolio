# Portfolio Website

This project is now organized like a standard static website.

## Structure

- `index.html`: Main page of the website.
- `assets/css/styles.css`: All website styles.
- `assets/js/main.js`: Starter JavaScript file.
- `assets/docs/cv-placeholder.html`: Temporary CV placeholder page.
- `assets/images/`: Images used by the website.

## Current tree

```
portfolio/
├── index.html
├── README.md
└── assets/
	├── css/
	│   └── styles.css
	├── js/
	│   └── main.js
	├── docs/
	│   └── cv-placeholder.html
	└── images/
		├── fanamby-hero.jpeg
		├── gdg-cape-town.jpeg
		├── govstack-wigtc.jpeg
		├── hack4dev.jpeg
		├── sesame-program.jpeg
		└── stupid-hackathon.jpeg
```

## How to open it

1. Open `index.html` in your browser.
2. Or, use the VS Code Live Server extension for auto-refresh while editing.

## Where to put new files

- New images: `assets/images/`
- New CSS files: `assets/css/`
- New JavaScript files: `assets/js/`
- CV and downloadable documents: `assets/docs/`

## GitHub Pages deployment

This repo now includes an automated deploy workflow at:

- `.github/workflows/deploy-pages.yml`

To publish your site:

1. Push your code to the `main` branch on GitHub.
2. In your GitHub repository, go to **Settings > Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Wait for the workflow to finish in the **Actions** tab.
5. Your site will be available at your GitHub Pages URL.
