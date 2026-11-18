# CloudLaunch sample website

A responsive landing page built with plain HTML, CSS and JavaScript. It is suitable as the source code for a beginner AWS CI/CD exercise.

## Files

- `index.html` — page structure and content
- `styles.css` — layout, colours, responsive styling
- `script.js` — mobile navigation and dynamic footer year

## Run locally

Open `index.html` in a browser. No build tools or dependencies are required.

## Deploy to Amazon S3

1. Create an S3 bucket and enable static website hosting.
2. Set `index.html` as the index document.
3. Upload `index.html`, `styles.css` and `script.js` to the bucket.
4. Configure the appropriate bucket access for your chosen hosting approach.
5. Open the S3 website endpoint to test the site.

For a real production website, consider using Amazon CloudFront with Origin Access Control rather than making the S3 bucket publicly accessible. Review AWS pricing before enabling services.
