# Heard Website — Launch Site

This package expands the existing Heard GitHub Pages coming-soon site into a complete static launch website while preserving its established visual language: midnight navy, electric blue, the real Heard app icon, and the Earth-horizon artwork.

## Included

- `index.html` — production marketing homepage using real app screenshots
- `privacy/` — App Store privacy-policy URL
- `support/` — App Store support URL and troubleshooting
- `data-sources/` — APRS-IS, FCC, ISED, QRZ, and Apple Maps acknowledgements
- `legacy-coming-soon.html` — a lightweight backup of the original landing page
- responsive CSS, navigation, image lightbox, metadata, favicons, web manifest, 404 page

## Publish to the existing repository

1. On the Mac, open the existing `Heard-website` folder.
2. Commit the current site first so it is preserved.
3. Create a branch such as `launch-site`.
4. Copy these files into the existing repository, replacing `index.html` and adding the new folders.
5. Preview locally or through GitHub Pages.
6. Commit and push when satisfied.

The site uses only relative links, so it works both at the current GitHub Pages project URL and later at `heard.ghostwind.app`.

## Custom domain later

Do not add a `CNAME` file until `ghostwind.app` is purchased and the `heard` DNS record is configured. Then create a root-level `CNAME` file containing:

```
heard.ghostwind.app
```

Configure the custom domain in GitHub Pages and enable HTTPS after DNS verification.

## Launch updates still needed

- Replace the App Store placeholder CTA with the official App Store badge and final App Store URL.
- Confirm `support@ghostwind.app` is active before public launch.
- Confirm any optional APRS-IS passcode, QRZ credential, or similar sensitive value is stored with Apple Keychain in the shipping build.
- Review the privacy policy against the final shipping build and App Store privacy answers.
- Review directory licensing/attribution language before release.
- Update effective dates when the final site goes live.

## Notes

- Real Heard screenshots are used without redrawing or stretching the app UI.
- The website contains no analytics, cookies, trackers, frameworks, or external font requests.
- Privacy-policy text is a product-specific draft, not legal advice.
