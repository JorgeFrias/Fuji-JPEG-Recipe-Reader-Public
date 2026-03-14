# Fuji Recipe Extractor Public Assets

This repo hosts the public web pages used by App Store Connect for:

- Marketing URL
- Privacy Policy URL

## Files

- `index.html`: Marketing page
- `privacy-policy.html`: Privacy policy page
- `styles.css`: Shared styles for both pages

## Publish On GitHub Pages

1. Push this repository to GitHub.
2. In repository settings, open **Pages**.
3. Set source to **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**.
5. Save and wait for the deployment URL.

## URLs For App Store Connect

If your GitHub Pages URL is:

`https://jorgefrias.github.io/Fuji-Recipe-Extractor-Public/`

Use:

- Marketing URL: `https://jorgefrias.github.io/Fuji-Recipe-Extractor-Public/`
- Privacy Policy URL: `https://jorgefrias.github.io/Fuji-Recipe-Extractor-Public/privacy-policy.html`

## Fastlane Metadata Mapping

Update these files in your app repo:

- `fastlane/metadata/en-US/marketing_url.txt`
- `fastlane/metadata/en-US/privacy_url.txt`
