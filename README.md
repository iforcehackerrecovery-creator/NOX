# CyberNox GreyHat Website

A responsive cybersecurity website using the supplied CyberNox GreyHat artwork as branding and section backgrounds.

## Files

- `index.html` — complete website
- `assets/` — CyberNox logo and cybersecurity background images

## Run locally

Open `index.html` in a modern browser.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload all files and the `assets` folder.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`.
6. Save and wait for GitHub Pages to publish.

## Contact form

The contact form is currently front-end only and displays a confirmation message. Connect it to a backend or form provider before using it to collect real messages.

## Branding

The website uses the supplied CyberNox GreyHat images as:
- Hero binary-code background
- About section hacker background
- Contact section cyber-studio background
- Service-card backgrounds
- Header/footer logo artwork


## Contact form email delivery

The Contact form is configured to submit requests through FormSubmit to `Vomeria@mail.com`.
On the first submission, FormSubmit may send an activation/confirmation email to the destination
address before delivery is enabled. No email password is stored in the website.

The `_next` field currently returns visitors to:
`https://etical-zenith-hackers.github.io/active/`

If this site is published at a different URL, change the `_next` value in `index.html`.
