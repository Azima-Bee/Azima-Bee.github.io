# Azima Bee - Static Portfolio

## Files
- `index.html` - main portfolio page
- `style.css` - responsive styling
- `script.js` - mobile navigation and footer year
- `assets/` - place your profile photo/resume here if needed

## AWS S3 Static Website Hosting
1. Create an S3 bucket.
2. Upload `index.html`, `style.css`, `script.js`, and the `assets` folder.
3. In **Properties**, enable **Static website hosting**.
4. Set the index document to `index.html`.
5. Configure the bucket's access policy/public access according to your AWS setup.
6. Open the S3 website endpoint.

For a production setup, CloudFront + HTTPS is recommended.

## Before publishing
- Replace the LinkedIn placeholder URL with your profile.
- Add `assets/profile.jpg` if you want to use a real photo.
- Add `assets/resume.pdf` and create a resume button if desired.
