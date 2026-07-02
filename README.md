# VergeOverrunUK GitHub Pages template

A static, responsive landing page for **VergeOverrunUK**, configured for **vergeoverrun.uk**. It is designed to work directly on GitHub Pages with no build step.

## Files

- `index.html` — page markup and content sections
- `styles.css` — responsive styling and theme colours
- `script.js` — mobile menu behaviour
- `assets/logo.svg` — circular Union Jack style community mark
- `assets/verge-placeholder.svg` — editable hero background placeholder
- `CNAME` — custom domain file for `vergeoverrun.uk`

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `vergeoverrunuk`.
2. Upload all files from this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/root`, then save.
6. In **Custom domain**, enter `vergeoverrun.uk`. The included `CNAME` file already contains this domain.
7. In your DNS provider, point `vergeoverrun.uk` to GitHub Pages using the current DNS records recommended in GitHub Pages documentation, then wait for DNS to propagate and enable HTTPS in Pages settings.

## Customise

- Replace the Formspree placeholder in `index.html` with a live form endpoint.
- Swap `assets/verge-placeholder.svg` for your own verge/roadside image.
- Replace `hello@example.org` with your contact email.
- Update the resource links to your preferred council reporting guidance and community rules.
