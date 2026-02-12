# OTI NGR Ltd - Landing Page

Professional landing page for OTI NGR Ltd polypropylene export business.

## Deployment to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it `oti-ngr-website` (or any name you prefer)
   - Make it **Public** (required for free GitHub Pages)
   - Click "Create repository"

2. **Upload files**
   - Click "uploading an existing file" link
   - Drag and drop all files from this folder
   - Click "Commit changes"

3. **Enable GitHub Pages**
   - Go to repository **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your site**
   - Your site will be live at: `https://YOUR-USERNAME.github.io/oti-ngr-website/`
   - It may take 1-2 minutes to deploy

### Option 2: Using Git Command Line

```bash
# Clone or initialize repository
git init
git add .
git commit -m "Initial commit - OTI NGR landing page"

# Add remote and push
git remote add origin https://github.com/YOUR-USERNAME/oti-ngr-website.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in Settings as described above.

## Customization

### Update Contact Information
Edit `index.html` and search for these placeholders:
- `trade@otingr.com` - Replace with actual email
- `+234 XXX XXX XXXX` - Replace with actual phone number
- `Lagos, Nigeria` - Update if different location

### Set Up Contact Form (Formspree)
The form is pre-configured with Formspree. To receive submissions:

1. Go to [formspree.io](https://formspree.io) and sign up (free)
2. Create a new form and copy your form ID (e.g., `xyzgowka`)
3. In `index.html`, find this line:
   ```html
   <form action="https://formspree.io/f/xyzgowka" method="POST">
   ```
4. Replace `xyzgowka` with your actual form ID
5. Update the redirect URL in `_next` field to your actual GitHub Pages URL

Form submissions will be sent directly to your Formspree dashboard and email.

### Custom Domain (Optional)
1. Add your domain to the `CNAME` file
2. Configure DNS with your domain registrar:
   - Add a CNAME record pointing to `YOUR-USERNAME.github.io`
3. Enable HTTPS in GitHub Pages settings

## Files Included

- `index.html` - Main landing page (all-in-one HTML/CSS)
- `.nojekyll` - Prevents Jekyll processing
- `README.md` - This file

## Design Features

- Executive/corporate aesthetic with navy blue and gold color scheme
- Fully responsive (mobile, tablet, desktop)
- Modern CSS with smooth animations
- Professional typography (Playfair Display + Inter)
- No external dependencies except Google Fonts

## Support

For questions about deployment, contact your web administrator.

---
© 2026 OTI NGR Ltd
