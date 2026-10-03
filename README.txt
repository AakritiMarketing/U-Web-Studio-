U-Web website - fast version for GitHub Pages
==============================================
Upload EVERYTHING in this folder to your GitHub repository (replace the old index.html):
  index.html      the website (small, about 450 KB)
  images/         110 photos as separate .webp files (each loads only when it is shown)
  .nojekyll       tells GitHub to serve the files as they are

To rebuild after you change photos: run  python uweb_make_site.py index.html uweb_images U-Web-site-for-GitHub
