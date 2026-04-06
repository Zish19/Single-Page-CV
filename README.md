# Single-Page CV

A clean, single-page Curriculum Vitae built with semantic HTML. This project focuses purely on structure and markup — no CSS or JavaScript — making it an ideal foundation for future styling.

## Preview

The CV includes the following sections:

- Header with name, title, and contact links
- About Me summary
- Skills (Languages, Frameworks, Tools, Soft Skills)
- Education history
- Career history with roles and responsibilities
- Notable projects with descriptions
- Certifications
- Languages spoken

## Features

- **Semantic HTML5** -- Uses meaningful tags such as `<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`, and `<time>` for a well-structured, accessible document.
- **SEO Meta Tags** -- Includes `description`, `keywords`, `author`, and `viewport` meta tags to improve search engine discoverability.
- **Open Graph Tags** -- Configured with `og:title`, `og:description`, `og:type`, `og:url`, `og:image`, and `og:locale` for rich previews when shared on social media.
- **Favicon Support** -- Links to both `.ico` and `.png` favicon formats in the document head.
- **Single-Page Layout** -- All content lives on a single page, separated by semantic sections and horizontal rules for readability.

## Project Structure

```
Single-Page CV/
  index.html    -- The complete single-page CV
  README.md     -- This file
```

## Getting Started

No build tools or dependencies are required. Simply open `index.html` in any modern web browser.

```bash
# Clone the repository
git clone https://github.com/your-username/single-page-cv.git

# Open in your browser
open index.html
```

## Customization

To make this CV your own:

1. Open `index.html` in a text editor.
2. Replace the placeholder name, contact details, and social links in the `<header>`.
3. Update the `<meta>` and Open Graph tags in the `<head>` to reflect your information.
4. Edit each `<section>` with your own education, skills, experience, projects, and certifications.
5. Add your own favicon files (`favicon.ico`, `favicon-32x32.png`) to the project root.

## Roadmap

This project is the first step in a multi-part series:

1. **HTML Structure** (this project) -- Build a semantic, single-page CV.
2. **CSS Styling** -- Apply visual design, typography, and layout.
3. **Responsive Design** -- Ensure the CV looks great on all screen sizes.

## License

This project is open source and available under the [MIT License](LICENSE).
