# Gather — Conference room booking

A responsive, single-page room booking app that runs on GitHub Pages. Browse six rooms, search their amenities, filter by capacity or video setup, view a sample day, and create bookings with overlap checks. The interface adds pointer-responsive 3D room cards, a dimensional animated welcome panel, staggered entrances, and spring-like modal and button transitions, with reduced-motion support. Demo bookings are included so the dashboard feels alive on first launch. New bookings are saved in the current browser using local storage.

## Launch on GitHub Pages

1. Create a GitHub repository and add `index.html`, `style.css`, and `app.js` to its root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Open the Pages URL GitHub provides.

No build step, packages, API keys, or server are required. You can also open `index.html` locally.

## Data note

This is a front-end demo. Bookings are stored in the browser where they were created; they are not shared across browsers or teammates. Team-wide booking needs a backend and authenticated shared database.