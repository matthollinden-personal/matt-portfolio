# Matt Hollinden — portfolio draft

A responsive, one-page portfolio for digital product management applications. Built with plain HTML and CSS; no dependency installation or build step is required.

## Run the preview

From `/workspace/matt-portfolio`:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

The page is served on port 3000. Use your environment's preview mechanism if available. You can also open `index.html` directly in a browser.

## Content review

See [the content draft](docs/content-draft.md) for source notes and missing information. The Mobile Parking Lot case study and contact email use user-confirmed information. The supplied résumé is available as a PDF download, and the introduction and about section reflect its product leadership and education details. No metrics are invented. The LinkedIn URL is user supplied; its profile content has not been reviewed.

The résumé is stored at `assets/matt-hollinden-resume.pdf`. The email link uses the confirmed public address. The résumé contains a phone number as supplied; the page itself lists only email and LinkedIn.

## Validation

Verified in Chromium: successful page response, section and résumé navigation, valid internal anchor targets, no browser errors, and no horizontal overflow at 375, 768, and 1440 pixel widths. No automated application test suite is needed for the current static page.
