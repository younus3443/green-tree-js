# The Green Tree Initiative 

Simple static site showing the climate initiative landing page (`home.html`) and donation form (`donation.html`).

## Features
- Hero banner with #STOPCLIMATECHANGE call to action.
- Sections for learn/volunteer/share/donate plus three “What We Do” cards.
- “Did you know?” stats, story card, events/news cards, and email subscribe strip.
- Donation page capturing personal and payment info with a single CTA button.
- Shared global/header/footer styles plus page-specific CSS under 

## Project Structure
```
Green Tree Initiative/
├── home.html
├── style.css
├── donation.html
├── donation.css
├── assets/
|   ├── home/
|   ├── about-us/
|   └── donation/
├── .gitignore
└── README.md
```

## Getting Started
1. **Prerequisites:** A modern web browser. No build tooling is required.
2. **Open locally:** Double-click `home.html` (or `donation.html`).
3. **Navigate:** Use the “Donate Today” button in the header to move between the landing page and the donation form.

## Customization
- Update copy directly in the HTML.
- Swap images under `assets/` (match filenames or update paths).
- Adjust section-specific CSS inside the scoped files to keep changes isolated.

## Contributing
1. Fork or clone the repo.
2. Create a feature branch (`git checkout -b feature/your-idea`).
3. Make changes, run formatting/linting if applicable.
4. Submit a pull request with a summary of the updates.

## 🌍 Netlify Deployment Configuration

This project is deployed using GitHub → Netlify integration.

Because the site files are inside a subfolder, Netlify needs a configuration file to define the publish directory.

netlify.toml
[build]
  publish = "green-tree-project"

This tells Netlify to:

- Look inside the green-tree-project folder

- Serve index.html as the main entry page

- Prevent 404 errors during deployment


