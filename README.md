# Slouch AI Website

Landing page for Slouch AI - an AI-powered posture tracking app.

## Deployment

This website is designed to be deployed on GitHub Pages.

### Setup Instructions:

1. Create a new GitHub repository named `slouchai-website` or similar
2. Push this `website` folder to the repository
3. Go to Settings → Pages in your GitHub repository
4. Set Source to "Deploy from a branch"
5. Select the main/master branch and root folder
6. Click Save

The website will be available at:
- `https://[your-username].github.io/[repository-name]/` (default)
- `https://slouchai.app` (if you configure the custom domain in the CNAME file)

### Custom Domain Setup:

1. Update the CNAME file with your actual domain
2. Configure your domain's DNS settings:
   - Add a CNAME record pointing to `[your-username].github.io`
   - Or add A records pointing to GitHub's IP addresses
3. Enable HTTPS in GitHub Pages settings

### Files:

- `index.html` - Main landing page
- `privacy.html` - Privacy Policy
- `terms.html` - Terms and Conditions
- `styles.css` - CSS styling
- `CNAME` - Custom domain configuration (update with your domain)
- `.nojekyll` - Disables Jekyll processing

### Updates Needed:

1. Replace `YOUR_APP_ID` in index.html with your actual App Store ID
2. Replace `YOUR_FORM_ID` in index.html with a Formspree form ID or other form handler
3. Update email addresses if different from the defaults
4. Update the CNAME file with your actual domain (or delete if not using custom domain)