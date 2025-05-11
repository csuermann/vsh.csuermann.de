# Virtual Smart Home Website

This is the website for Virtual Smart Home, built with Jekyll and hosted on GitHub Pages.

## Local Development

To run the site locally, you'll need to have Ruby and Bundler installed. Then follow these steps:

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Start the local development server:
   ```bash
   bundle exec jekyll serve
   ```

3. Open your browser and navigate to `http://localhost:4000`

## Project Structure

- `_config.yml` - Jekyll configuration file
- `_layouts/` - Contains the default layout template
- `_includes/` - Contains reusable components
- `*.html` - Individual pages using the Jekyll layout
- `styles.css` - Main stylesheet
- `*.png`, `*.svg`, `*.ico` - Static assets

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch. The deployment is handled by GitHub Actions.

## License

All rights reserved. This project and its contents are proprietary and confidential. 