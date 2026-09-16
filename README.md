[README-GitHub.md](https://github.com/user-attachments/files/32307614/README-GitHub.md)
# East Fort Worth Voters PAC Website

This package contains a complete static website for **EFWVotersPac.org**.

## Files in the website folder

- `index.html` — page content and contact form
- `styles.css` — colors, typography, desktop and mobile layout
- `script.js` — mobile navigation and footer year
- `assets/east-fort-worth-community.png` — hero image

Keep these files and the `assets` folder together. Do not rename or move the image unless you also update its path in `index.html`.

## Before launch

1. Confirm that `president@efwvoterspac.org` can receive email.
2. Ask the PAC treasurer or counsel to confirm the legal name and required political-advertising disclaimer. The current footer reads: “Political advertising paid for by East Fort Worth Voters PAC.”
3. Review the mission, About Us text, and privacy promise.

## Upload through GoDaddy Web Hosting (cPanel)

These steps apply if the GoDaddy account includes **Web Hosting (cPanel)**. A domain registration by itself does not provide a place to upload website files.

1. Sign in to GoDaddy and open **My Products**.
2. Under **Web Hosting**, select **Manage** next to the hosting account.
3. Open the website menu and select **File Manager**.
4. Open the website's root directory. For a primary domain, this is commonly `public_html`; GoDaddy may show a different root for an added domain.
5. Download and unzip `EFW-Voters-PAC-Website.zip` on your computer.
6. Upload the *contents* of its `website` folder into the root directory: `index.html`, `styles.css`, `script.js`, and the `assets` folder. Do not upload the outer `website` folder itself unless you want the site to appear at `/website/`.
7. If an old placeholder home page is present, rename it as a backup or remove it after confirming you no longer need it. Do not overwrite unrelated folders.
8. Visit `https://EFWVotersPac.org` in a private browser window. Confirm the image, navigation, and form appear correctly.

## Activate the inquiry form

The form uses FormSubmit to forward messages to `president@efwvoterspac.org`.

1. Submit one test inquiry from the live website.
2. Check `president@efwvoterspac.org` for FormSubmit's confirmation message, including spam or junk folders.
3. Open the confirmation link.
4. Submit a second test inquiry and verify it arrives correctly.

The direct email link on the page remains available if the form relay is not yet activated.

## Launch checklist

- Confirm the site opens with `https://` and no browser warning.
- Test the site on a phone and desktop.
- Test all navigation links.
- Activate and test the inquiry form.
- Verify the political-advertising disclaimer with the PAC treasurer or counsel.
- Keep a copy of the ZIP file before making future changes.

## Editing

Open `index.html` in a plain-text or code editor to change wording. Open `styles.css` to change colors or layout. Save a backup before replacing the live files.
