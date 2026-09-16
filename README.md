# Tech Nest Website

Static, responsive Tech Nest website designed for GitHub Pages.

## Files
- `index.html` — complete website, CSS and JavaScript in one file.

## Publish on GitHub Pages
1. Create a new GitHub repository, e.g. `technest-website`.
2. Upload `index.html` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save and wait for GitHub Pages to deploy.
7. Your site will be available at the GitHub Pages URL.

## Before publishing
Open `index.html` and replace:
- `YOUR_EMAIL@example.com`
- `YOUR PHONE NUMBER`
- `https://technest.co.za` if the final domain differs.

## Custom domain
If your final domain is `technest.co.za`, add a file named `CNAME` containing:

technest.co.za

Then configure the domain's DNS records at the domain provider according to GitHub Pages' current custom-domain instructions.

## Contact form
The current version uses `mailto:` so no server is required. For true website form submissions without opening the visitor's email application, connect a service such as Formspree or Web3Forms and replace the submit handler.
