# Voyage Website

A responsive restaurant website project built with HTML, CSS, and PHP for newsletter and reservation form handling.

## Project Overview

- **Project name:** Voyage
- **Pages included:**
  - `index.html` — main homepage
  - `pages/menu.html` — menu page
  - `pages/newsletter.html` — newsletter page
  - `pages/our-chefs.html` — chef showcase page
  - `pages/reservation-fail.html` — reservation error page
- **Server-side files:**
  - `newsletter.php` — newsletter form processing
  - `reservation.php` — reservation form processing

## Files and Structure

- `assets/css/style.css` — main stylesheet
- `assets/css/our-chefs.css` — chef page stylesheet
- `assets/js/script.js` — custom page scripts
- `assets/images/` — image assets used throughout the site
- `tailwind.config.js` — Tailwind CSS configuration file
- `style-guide.md` — project styling notes and guidelines
- `web/` — additional web resources

## Getting Started

1. Open the project folder in your code editor.
2. To preview static pages, open `index.html` or other `.html` files in a browser.
3. To test PHP forms, run a local PHP-enabled server, for example:

```bash
php -S localhost:8000
```

Then open `http://localhost:8000/index.html`.

## Notes

- Ensure the `assets` folder remains in the project root so styles and images load correctly.
- Use a PHP server when using `newsletter.php` or `reservation.php`.

## License

This repository does not include a license. Add one if you want to share or distribute the project publicly.
