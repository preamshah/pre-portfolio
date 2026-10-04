# Pream Shah — Personal Portfolio

A personal portfolio website for **Pream Shah**, showcasing an introduction, technical skills, selected projects, and contact/social links.

## About the Project

This is a static front-end portfolio built with HTML, CSS, and JavaScript. The supplied `index.html` includes Home, About Me, Skills, Projects, and Contact/Social sections, with animated elements and local media assets.

## Features

- Responsive personal portfolio layout
- Home and About Me sections
- Technical skills and tools showcase
- Selected projects with preview images
- Email contact link and social profile links
- Animated page elements using AOS
- Appearance and sound controls
- Résumé link
- Google Analytics integration (configured in the supplied HTML)

## Technology Stack

- **HTML5** — page structure
- **CSS3** — styling (`style.css`)
- **JavaScript** — interactive behavior (`main.js` and inline scripts)
- **AOS** — scroll animations, loaded from a CDN
- **Google Fonts** — typography, loaded from Google Fonts
- **Google Analytics** — website analytics, if the configured ID is yours and you intend to use it

The supplied HTML does not indicate a required package manager or build step. Keep any existing project files and asset paths intact.

## Project Structure

The following structure reflects paths referenced in the supplied `index.html`. Some folders may contain additional files in your local project.

```text
.
├── index.html
├── style.css
├── main.js
├── README.md
├── SECURITY.md
└── src/
    ├── ico/
    ├── mp3/
    ├── pdf/
    ├── png/
    ├── svg/
    └── webp/
```

The page references assets such as the favicon, profile images, project previews, audio, and `src/pdf/Resume.pdf`. Ensure these files exist at the referenced paths, or update the HTML to match your actual filenames.

## Run Locally

1. Download or clone the repository.
2. Keep `index.html`, `style.css`, `main.js`, and the `src/` assets in their expected relative locations.
3. Open `index.html` in a browser, or run it using a local static server such as the **Live Server** extension in Visual Studio Code.
4. Test the navigation, animations, project images, appearance/sound controls, résumé link, and contact/social links.

No dependency installation is required for the supplied static HTML unless you add a build tool or package-based dependencies later.

## Deployment

You can deploy this static website using GitHub Pages or another static hosting service.

### GitHub Pages

1. Push the project files to a GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Choose the appropriate deployment source and branch/folder containing `index.html`.
4. Save the settings and wait for the deployment to finish.
5. Open the published URL and verify all assets and links.

If you publish the website under a repository subpath, check that all relative asset paths work correctly.

## Before Publishing

- [ ] Confirm all referenced images, icons, audio, CSS, JavaScript, and résumé files are present.
- [ ] Replace template content, names, links, or branding that do not belong to you.
- [ ] Verify email addresses and social profile URLs.
- [ ] Confirm the Google Analytics measurement ID and Google site-verification token belong to you. Remove them if not needed or not yours.
- [ ] Check that the résumé and all public files contain no private or sensitive information.
- [ ] Test on desktop, tablet, and mobile screen sizes.
- [ ] Review licenses and permissions for third-party fonts, libraries, images, audio, and project previews.
- [ ] Add a separate `LICENSE` file only after choosing license terms that you have the right to apply.

## Privacy

The supplied HTML loads Google Analytics. Analytics may collect information about visitors depending on the configuration. Review Google's current documentation and the privacy requirements that apply to your audience, and provide appropriate disclosures or consent controls where required.

## Security

See [SECURITY.md](SECURITY.md) for instructions on reporting potential vulnerabilities and general security considerations.

## Credits

Portfolio text, project descriptions, and links should be reviewed by the repository owner before publication. Third-party libraries and media remain subject to their own licenses and terms.
