# Gemini Project Analysis

This directory contains a web-based application for visualizing BIM models in Augmented Reality.

## `webDev-modelViewer`

*   **Project Overview:** A web-based application for visualizing BIM models in Augmented Reality. It uses `vite` for the build process and `leaflet` to display a map with model locations. The `index.html` file sets up the basic page structure with a disclaimer and a main container, and the `src/main.css` file provides the styling for the application. The core functionality is to fetch model data from `public/models.json`, display markers on a map, and then launch an AR view using `<model-viewer>` when a marker is clicked. The `vite.config.js` file is configured with a `base` path of `/modelViewerBIM/` for deployment, and the `.github/workflows/deploy.yml` file automates deployment to GitHub Pages.
*   **Building and Running:**
    *   `npm install`: Install dependencies.
    *   `npm run dev`: Start the development server.
    *   `npm run build`: Build the project for production.
    *   `npm run preview`: Preview the production build.
*   **Development Conventions:** The code is modular, with a clear separation of concerns in `src/main.js`. It uses modern JavaScript features like `async/await` and is structured as a single-page application.
