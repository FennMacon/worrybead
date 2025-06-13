# Quick Update Guide for Worry Bead Records Website

## Easy Updates (No Technical Knowledge Required)

### 1. Adding a New Release

**Step 1:** Open `index.html` in any text editor
**Step 2:** Find the "Releases" section (around line 30)
**Step 3:** Copy an existing release card and modify:

```html
<div class="release-card">
    <div class="release-content">
        <h3>YOUR ALBUM TITLE</h3>
        <p class="release-date">RELEASE DATE</p>
        <p class="release-description">DESCRIPTION OF THE ALBUM</p>
    </div>
    <div class="bandcamp-embed">
        <!-- Paste Bandcamp embed code here -->
    </div>
    <a href="BANDCAMP_URL" target="_blank" class="button">View on Bandcamp</a>
</div>
```

### 2. Adding Press Coverage

**Step 1:** Open `index.html`
**Step 2:** Find the "Press" section (around line 60)
**Step 3:** Add a new press item:

```html
<article class="press-item">
    <h3>PUBLICATION NAME</h3>
    <p>ARTICLE TITLE OR DESCRIPTION</p>
    <a href="ARTICLE_URL" target="_blank">Read More</a>
</article>
```

### 3. Adding a New Video

**Step 1:** Open `index.html`
**Step 2:** Find the "Videos" section (around line 55)
**Step 3:** Add a new video card:

```html
<div class="video-card">
    <h3>ARTIST - "SONG TITLE"</h3>
    <p class="video-description">DESCRIPTION OF THE VIDEO</p>
    <div class="video-embed">
        <!-- Paste YouTube embed code here -->
    </div>
</div>
```

## Publishing Updates

### Option 1: GitHub Desktop (Recommended for Beginners)
1. Download [GitHub Desktop](https://desktop.github.com/)
2. Clone your repository
3. Make changes to files
4. Commit and push changes

### Option 2: Command Line
```bash
git add .
git commit -m "Description of your changes"
git push origin main
```

### Option 3: GitHub Web Interface
1. Go to your repository on GitHub
2. Click on the file you want to edit
3. Click the pencil icon to edit
4. Make changes and commit

## Setting Up Automatic Deployment

For easy updates, consider:

1. **GitHub Pages**: Free hosting directly from your repository
2. **Netlify**: Connect to GitHub for automatic deployments
3. **Vercel**: Similar to Netlify with easy GitHub integration

## Need Help?

- Check the README.md for detailed instructions
- Create an issue on GitHub if you run into problems
- The website structure is simple HTML/CSS - easy to modify!

## Quick Backup

Before making major changes:
1. Download a copy of your files
2. Or create a new branch in Git: `git checkout -b backup-date`

---

Remember: Test your changes by opening `index.html` in a web browser before publishing! 