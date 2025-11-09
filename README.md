# Riverplace-index.html
Frankenmuth River Place Business Directory - An interactive map-based directory showcasing local businesses

## 🌐 Accessing Your Live Website

Your website can be accessed via GitHub Pages at:

**https://tomzapata50-cmd.github.io/Riverplace-index.html/**

### How to Enable GitHub Pages (if not already enabled)

1. Go to your repository on GitHub: https://github.com/tomzapata50-cmd/Riverplace-index.html
2. Click on **Settings** (top menu)
3. In the left sidebar, click on **Pages**
4. Under "Source", select the branch to deploy (usually `main` or `master`)
5. Select the folder: `/ (root)`
6. Click **Save**
7. Wait a few minutes for GitHub to build and deploy your site
8. Your site will be live at: https://tomzapata50-cmd.github.io/Riverplace-index.html/

### 📱 Features

- Interactive map showing business locations in Frankenmuth River Place
- Search and filter functionality
- Mobile-friendly responsive design
- Real-time business directory with hours and directions
- Click on businesses to see location on map
- Direct Google Maps integration for directions

### 🚀 Quick Start for Local Development

To view this website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/tomzapata50-cmd/Riverplace-index.html.git
   ```

2. Open `index.html` in your web browser

That's it! The site uses pure HTML, CSS, and JavaScript - no build process required.

### 📝 Updating Your Website

After making changes to `index.html` or other files:

1. Commit your changes:
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

2. Push to GitHub:
   ```bash
   git push origin main
   ```

3. GitHub Pages will automatically update your live site within a few minutes

### 🗺️ Customizing Business Data

To add or edit businesses, modify the `businesses` array in `index.html` (around line 132). Each business has:
- `name`: Business name
- `type`: Category (Restaurant, Specialty Food, Shop)
- `featured`: Highlight as featured (true/false)
- `premium`: Show premium badge (true/false)
- `desc`: Short description
- `hours`: Operating hours
- `coords`: [latitude, longitude] for map location

### 🛠️ Troubleshooting

**Site not loading?**
- Make sure GitHub Pages is enabled in repository Settings > Pages
- Check that the source branch is correct
- Wait 2-5 minutes after enabling or pushing changes

**Changes not appearing?**
- Clear your browser cache (Ctrl+F5 or Cmd+Shift+R)
- Wait a few minutes for GitHub Pages to rebuild
- Check that changes were pushed to the correct branch

**Need help?**
- Check GitHub Pages status: Settings > Pages
- Review repository Actions tab for build status
- Ensure index.html is in the root directory
