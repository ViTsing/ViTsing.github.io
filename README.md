# Academic Homepage

This is the source code for Ming Dong's academic homepage, built with Hugo.

## Local Development

1. Install Hugo (extended version):
   ```bash
   # For macOS
   brew install hugo
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/ViTsing/ViTsing.github.io.git
   cd ViTsing.github.io
   ```

3. Start the Hugo server:
   ```bash
   hugo server -D
   ```

4. View the site at http://localhost:1313/

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## Updating Content

The main content is in `content/_index.md`. To update the website:

1. Edit the markdown files in the `content` directory
2. Commit and push your changes
3. GitHub Actions will automatically build and deploy the site

## Structure

- `content/`: Contains the main content files
- `assets/css/`: Contains the custom CSS
- `layouts/`: Contains the HTML templates
- `config/`: Contains the Hugo configuration files

## License

Copyright © 2024 Ming Dong. All rights reserved. 