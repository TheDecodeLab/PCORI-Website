# PCORI-Website

A research website focused on improving stroke recovery in rural communities. This project is designed to be deployed on GitHub Pages.

## About

This website presents research findings and information about stroke recovery initiatives in rural communities, featuring:

- Research overview and methodology
- Team information and collaborations
- Interactive elements and resources
- Responsive design for all devices

## GitHub Pages Setup

This website is configured to work with GitHub Pages. To deploy:

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" or "master" branch and "/ (root)" folder
5. Click "Save"
6. Your site will be available at: `https://thedecodelab.github.io/PCORI-Website/`

## Local Development

To run this website locally, simply open `index.html` in your web browser or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

## Structure

- `index.html` - Main website file
- `audio/` - Audio resources
- `photos/` - Image assets
- `LICENSE` - Project license

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Responsive design principles