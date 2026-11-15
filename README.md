# Comunhão Rara — Website

Website of **Igreja Comunhão Rara**, with links to the church's services and a page to download the **Rara** mobile app.

![HTML](https://img.shields.io/badge/html-5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/css-3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-vanilla-F7DF1E?logo=javascript&logoColor=black)

## Demo

- **Website:** https://comunhaorara.com

## Features

- **Home page** with the church banner and links (social media, local media and partner websites).
- **"Download our app" page** with the Google Play link of the Rara app.
- **Privacy policy** page for the app.
- **Shared header and footer** loaded by JavaScript on every page.

## Tech stack

| Area | Technology |
|---|---|
| Pages | Plain HTML |
| Styles | Plain CSS + Google Fonts (Montserrat, Rajdhani) |
| Icons | Font Awesome |
| Scripts | Vanilla JavaScript |

No framework, no bundler and no `package.json`.

## Prerequisites

- A modern browser
- Optional: any static file server to test locally (for example `npx serve`)

## Installation

```bash
git clone <repository-url> rarasite
cd rarasite
npx serve .
```

Then open the address shown in the terminal. The header and footer are loaded with JavaScript, so use a local server instead of opening the files directly.

## Configuration

There are no environment variables. The website is public and must never contain secrets.

## Usage

- Edit the HTML/CSS files and refresh the browser: there is no build.
- To change the header or footer on every page, edit `component/header.html` / `component/footer.html`.

## Folder structure

```
rarasite/
├── index.html            # Home page
├── pages/                # Download the app, privacy policy
├── component/            # Shared header and footer (HTML + JS loader)
├── css/                  # Page styles
├── font/                 # Self-hosted font file
└── img/                  # Banner, app screenshots and icon
```

## Deployment

- Static hosting: publish the repository root as is (no build step).

## Contributing

1. Create a branch from `main`: `feature/<name>` (or `fix/<name>`).
2. Keep the shared header and footer in `component/`.
3. Test on a phone-sized screen.
4. Write commit messages in Portuguese and open a pull request to `main`.

## License and author

**Private and proprietary.** All rights reserved. Content and images belong to Igreja Comunhão Rara.

Developed by **Stanley Andrade**.
