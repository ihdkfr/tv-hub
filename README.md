# TV Hub

A custom, mobile-friendly movie streaming **design preview** for the family.

This repository holds the preview website. It is not the secure home-PC streaming server yet. The public Netlify preview uses sample titles and stores preferences in the current browser only.

## Website features
- Home, Movies, TV, Kids and other navigable pages
- Movie details, search, category filters and a player preview
- Family profiles and child-friendly browsing
- Favourites and watch progress in browser storage

## Hosting on the existing Netlify site
Connect this GitHub repository (`ihdkfr/tv-hub`) to your **existing** Netlify project. Set the branch to `main`, publish directory to `.` (repository root), and leave the build command empty. Netlify will automatically deploy future commits on `main`.

Do not upload paid film files, credentials or private data to this public static preview. Streaming actual media files from your home PC will require a separately secured backend and remote-access configuration.

## Local development
Serve the project directory using a static HTTP server, e.g. `python -m http.server 8000`, then open `http://localhost:8000`.