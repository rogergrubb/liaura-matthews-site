# Liaura Matthews — Personal Website

A beautiful, feminine personal bio website built with love.

## 🖼️ Adding Photos

The site has **7 photo placeholder spots** that need real photos of Liaura. Here's how to add them:

### Photo Spots (in order of importance):

| # | Location | Recommended Photo | Size/Shape |
|---|----------|-------------------|------------|
| 1 | **Hero Portrait** | Best portrait photo (head/shoulders) | Tall/vertical |
| 2 | **About - Main** | Casual lifestyle photo | Vertical (4:5) |
| 3 | **About - Small** | Fun candid shot | Square |
| 4 | **Gallery - Featured** | Full-length or scenic photo | Tall/vertical |
| 5 | **Gallery - Photo 2** | Social/friends photo | Square |
| 6 | **Gallery - Photo 3** | Travel or adventure | Square |
| 7 | **Gallery - Photo 4** | Professional/dressed up | Square |
| 8 | **Gallery - Photo 5** | Hobby or fun moment | Square |

### How to Replace Photos:

1. Add your photos to the `images/` folder
2. In `index.html`, search for `<!-- REPLACE:` comments
3. Uncomment the `<img>` tag below each comment
4. Update the `src` to point to your image file
5. Remove or comment out the `<div class="hero-image-placeholder">` or `<div class="img-placeholder">` block

**Example:**
```html
<!-- Before -->
<div class="hero-image-placeholder">...</div>

<!-- After -->
<img src="images/liaura-hero.jpg" alt="Liaura Matthews">
```

### Other Customizations:
- **Email**: Search for `hello@liauramatthews.com` and replace with real email
- **Social Links**: Update the Facebook/Instagram `href="#"` links
- **Quote**: Update the quote in the quote section if Liaura has a favorite saying
- **Bio Text**: Tweak any of the paragraph text in the About section

## 🚀 Deployment

This is a static site — just connect to Vercel and it deploys automatically.

## Tech
- Pure HTML/CSS/JS (no build step needed)
- Google Fonts (Playfair Display, Cormorant Garamond, Jost)
- Scroll animations via IntersectionObserver
- Fully responsive (mobile, tablet, desktop)
