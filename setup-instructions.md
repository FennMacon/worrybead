# Worry Bead Records - Decap CMS Setup Instructions

## What You've Got Now

Your site is now powered by **Jekyll + Decap CMS**, which means:
- ✅ Your beautiful design stays exactly the same
- ✅ Content is managed through a user-friendly admin interface
- ✅ Everything works with GitHub Pages (free hosting)
- ✅ Your end user gets a WordPress-like editing experience

## For the End User: How to Edit Content

### 1. Access the CMS
Go to: `https://yoursite.com/admin` (replace with your actual domain)

### 2. Login with GitHub
- The first time, you'll need to authorize with GitHub
- After that, it's one-click login

### 3. Edit Content
The admin interface has sections for:
- **News**: Add announcements, tour dates, etc.
- **Releases**: Add new albums with Bandcamp embeds
- **Videos**: Add YouTube videos or interactive experiences
- **Press**: Add press coverage and reviews
- **Pages**: Edit About page and Contact info

### 4. Publishing
- Click "Save" to save drafts
- Click "Publish" to make changes live
- Changes appear on the website within minutes

## Setup Steps for Developer

### 1. Update Repository Name
Edit `admin/config.yml` and change:
```yaml
backend:
  repo: worrybeadrecs/worrybead  # Change to YOUR_USERNAME/YOUR_REPO
```

### 2. Enable GitHub Pages
1. Go to your repo settings
2. Pages → Source → Deploy from branch
3. Select `main` branch
4. Your site will be at `https://yourusername.github.io/reponame`

### 3. Configure Authentication
Decap CMS uses GitHub for authentication. No additional setup needed!

### 4. Test the Setup
1. Push all changes to GitHub
2. Visit `https://yoursite.com/admin`
3. Login with GitHub
4. Try adding a news item

## Content Structure

### News Posts
- Automatically sorted by date (newest first)
- Can include links to external sites
- First post gets "featured" styling

### Releases
- Include Bandcamp embed codes
- Sorted by release date
- Support for featured releases

### Videos
- Support for YouTube embeds or interactive experiences
- Flexible button text

### Press
- Simple publication, title, and link structure
- Sorted by date

## Benefits for Your End User

1. **Easy to Use**: Interface similar to WordPress
2. **No Technical Knowledge Required**: Point and click editing
3. **Safe**: Can't break the site design
4. **Version Control**: All changes are tracked in Git
5. **Free**: No monthly CMS fees
6. **Fast**: Static site loads quickly
7. **Reliable**: Hosted on GitHub's infrastructure

## Troubleshooting

**Can't access /admin?**
- Make sure you've pushed all files to GitHub
- Check that GitHub Pages is enabled
- Verify the repo name in `admin/config.yml`

**Login not working?**
- User needs a GitHub account
- Make sure they have access to the repository

**Changes not appearing?**
- GitHub Pages can take a few minutes to update
- Check that changes were actually published (not just saved)

## Adding New Content Types

If you need additional content types (like Artists, Events, etc.), edit:
1. `admin/config.yml` - Add new collection
2. `_config.yml` - Add to collections list
3. `index.html` - Add display logic

---

Your site is now ready for easy content management! 🎵 