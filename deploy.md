# GitHub Pages Deployment Guide

## Quick Setup

1. **Initialize Git Repository** (if not already done):
   ```bash
   git init
   ```

2. **Add Remote Origin**:
   ```bash
   git remote add origin https://github.com/bevanjebanesan1-netizen/portfolio.git
   ```

3. **Add All Files**:
   ```bash
   git add .
   ```

4. **Commit Changes**:
   ```bash
   git commit -m "Initial portfolio website deployment"
   ```

5. **Set Main Branch**:
   ```bash
   git branch -M main
   ```

6. **Push to GitHub**:
   ```bash
   git push -u origin main
   ```

## Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/bevanjebanesan1-netizen/portfolio`
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

## Access Your Website

Your portfolio will be available at:
**https://bevanjebanesan1-netizen.github.io/portfolio/**

## Future Updates

To update your website:
```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

GitHub Pages will automatically rebuild and deploy your changes within a few minutes.

## Custom Domain (Optional)

If you want to use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable custom domain in GitHub Pages settings

## Troubleshooting

- **404 Error**: Make sure `index.html` is in the root directory
- **Styling Issues**: Check that `styles.css` is properly linked
- **JavaScript Errors**: Verify `script.js` is correctly referenced
- **Build Failures**: Check GitHub Actions tab for error details
