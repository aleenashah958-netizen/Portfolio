# Aleena Shah Portfolio - Deployment Guide

## Files Included

```
aleena-portfolio-deploy/
  index.html              <- Your full portfolio (self-contained)
  video.mp4               <- YOU NEED TO ADD THIS (your hero video)
  Media_gallery_.pdf      <- Your media gallery PDF (optional backup)
  README.md               <- This file
```

## Before Deploying

1. **Add your hero video**: Place your `video.mp4` file in this folder next to `index.html`. This is the video that plays in the hero section at the top of the site.

2. **That's it!** The media gallery flipbook images are already embedded in the HTML. All fonts load from Google Fonts CDN. No other files needed.

## How to Deploy (Free Options)

### Option A: Netlify (Recommended - Easiest)
1. Go to https://app.netlify.com
2. Sign up / log in (free)
3. Drag and drop this entire folder onto the page
4. Done! You'll get a link like `your-site.netlify.app`
5. You can set a custom domain later in Site Settings

### Option B: Vercel
1. Go to https://vercel.com
2. Sign up / log in (free)
3. Click "Add New" > "Project"
4. Upload this folder
5. Done! You'll get a link like `your-site.vercel.app`

### Option C: GitHub Pages (Free)
1. Create a GitHub account if you don't have one
2. Create a new repository (e.g., "portfolio")
3. Upload all files from this folder
4. Go to Settings > Pages > Source: "main" branch
5. Done! You'll get `yourusername.github.io/portfolio`

### Option D: Cloudflare Pages (Free)
1. Go to https://pages.cloudflare.com
2. Connect your GitHub or upload directly
3. Deploy

## Custom Domain

All the platforms above support free custom domains. If you buy a domain (e.g., aleenashah.com from Namecheap, Google Domains, etc.), you can point it to any of these hosting platforms.

## File Size Note

The index.html is ~2.8MB because it contains all 16 media gallery pages as embedded images. This is intentional so the flipbook works without any external dependencies. The page will still load fast since the images only render when you scroll to the gallery section.
