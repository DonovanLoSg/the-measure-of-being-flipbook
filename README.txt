THE MEASURE OF BEING — GITHUB PAGES FLIPBOOK

Upload index.html and the entire pages/ folder to the root of your repository:
https://github.com/DonovanLoSg/the-measure-of-being-flipbook

The repository must contain:
  index.html
  pages/page-01.jpg ... pages/page-57.jpg

GitHub Settings > Pages: publish from main / (root), or keep your existing working Pages deployment workflow.
GitHub Pages custom domain: flipbook.donovanlo.sg
Vodien DNS CNAME: flipbook -> donovanlosg.github.io

The viewer uses StPageFlip via the jsDelivr CDN and requires an internet connection.
The 57 page images are from the supplied book-preview.pdf. Do not upload the complete commercial book.
To test locally, run: python -m http.server 8000
Then visit http://localhost:8000

StPageFlip: https://github.com/Nodlik/StPageFlip (MIT License).
