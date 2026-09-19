# Deployment-ready Flutter web project

This project includes configuration for GitHub Pages, Firebase Hosting, and Netlify.

## GitHub Pages
1. Push the project to GitHub.
2. Open **Settings → Pages** and choose **GitHub Actions** as the source.
3. Push to `main` or `master`, or run the workflow manually.
4. The workflow builds Flutter web and publishes `build/web`.

The expected GitHub Pages URL is:
`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

## Local verification
Run:
`flutter pub get`
`flutter build web --release`

Then deploy the generated `build/web` directory with your hosting provider.

## Note
This is a UI clone and is not affiliated with Ethio Telecom or the official Telebirr service. Do not use it to collect real banking credentials, OTPs, PINs, or payment information.
