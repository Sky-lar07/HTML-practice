# HTML Practice Project

## Overview
This is a simple HTML practice project designed for learning and experimenting with HTML, CSS, and basic web development concepts. The project includes a responsive single-page website with multiple sections including navigation, content areas, and a contact form.

## Project Structure
```
.
├── index.html       # Main HTML file with semantic structure
├── styles.css       # CSS styling with modern design
└── README.md        # Original repository readme
```

## Technology Stack
- **Frontend**: Pure HTML5 and CSS3
- **Server**: Python's built-in HTTP server (for development)
- **Deployment**: Static site serving via Python HTTP server

## Current Features
- Semantic HTML structure with header, nav, main, sections, and footer
- Modern CSS styling with gradient backgrounds
- Responsive navigation menu
- Multiple content sections:
  - Home/Getting Started
  - About HTML (informational)
  - Contact form (HTML form elements)
- Mobile-friendly viewport configuration

## Development Setup
The project uses Python 3.11's built-in HTTP server to serve static files on port 5000.

**Workflow Configuration:**
- Name: Server
- Command: `python -m http.server 5000`
- Port: 5000 (frontend)
- Output Type: webview

## Deployment
The project is configured for Replit autoscale deployment, serving static HTML/CSS files via Python's HTTP server.

## Recent Changes
- **2025-10-05**: Initial project setup in Replit environment
  - Created index.html with semantic HTML structure
  - Added styles.css with modern gradient design
  - Configured Python HTTP server workflow
  - Set up deployment configuration
  - Added .gitignore for Replit-specific files

## Usage
The project is ready to use for HTML practice. Simply edit `index.html` to practice HTML elements and `styles.css` to practice CSS styling. The changes will be immediately visible when you refresh the preview.

## Architecture Notes
This is a static website project with no backend or database requirements. The Python HTTP server is used purely for serving static files during development and deployment.
