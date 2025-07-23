# Send To Myself Website

This is the official website for Send To Myself app.

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a new repository called `sendtomyself-website`
2. Upload these files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be available at: `https://yourusername.github.io/sendtomyself-website`

### Option 2: Netlify (Free)
1. Go to https://netlify.com
2. Sign up with GitHub
3. Click "New site from Git"
4. Choose your repository
5. Deploy settings: Build command: (leave empty), Publish directory: `website`
6. Your site will be available at: `https://your-site-name.netlify.app`

### Option 3: Vercel (Free)
1. Go to https://vercel.com
2. Sign up with GitHub
3. Click "New Project"
4. Import your repository
5. Deploy settings: Framework Preset: Other, Root Directory: `website`
6. Your site will be available at: `https://your-site-name.vercel.app`

## Custom Domain Setup

After deployment, you can set up a custom domain:
1. Purchase a domain (e.g., sendtomyself.app)
2. In your hosting provider's settings, add the custom domain
3. Update the DNS records as instructed

## App Store Connect URLs

Once deployed, use these URLs in App Store Connect:

- **Support URL**: `https://your-domain.com`
- **Marketing URL**: `https://your-domain.com`
- **Privacy Policy URL**: `https://your-domain.com/privacy.html`

## File Structure

```
website/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── downloads/          # App downloads folder
│   └── SendToMyself-macOS.dmg  # macOS app (to be added)
└── README.md          # This file
```

## Updates

To update the website:
1. Modify the HTML files
2. Commit and push to your repository
3. The hosting service will automatically redeploy

## macOS App Distribution

To distribute the macOS app:
1. Build the macOS app: `flutter build macos --release`
2. Create a DMG file from the built app
3. Upload the DMG to the `downloads/` folder
4. Update the download link in `index.html` 