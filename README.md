# studio-home
Studio Hub — Belmont AET

Live URL: https://bradwintersmusic-cloud.github.io/studio-home/

The main entry point for the Belmont University Audio Engineering Technology Studio Hub. A static launcher page linking to all tools, directories, and resources in the AET web suite.


Overview


Card grid layout on desktop (3 columns)
Single-column linktree-style layout on mobile
Animated radial gradient background (gold and blue orbs)
No data dependencies — fully static HTML



Adding a New Page

To add a new card to the launcher, open index.html and find the .card-grid div. Copy an existing hub-card block and update:


href — URL of the new page
The SVG icon inside .card-icon-wrap
.card-name — display name
.card-desc — one-line description



Maintenance

This page has no external data sources. Any update requires editing index.html and pushing to main. GitHub Pages deploys automatically on push.


Tech Stack


Static HTML / CSS / JS
GitHub Pages hosting
IBM Plex Mono + Inter (Google Fonts)



Repo

bradwintersmusic-cloud/studio-home
Maintained by Brad Winters