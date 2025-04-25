# CRTD Website

A simple static website for CRTD, hosted on GitHub Pages.

## Setup Instructions

1. Fork this repository to your GitHub account
2. Go to your repository settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "main" branch and click "Save"
5. Your website will be available at `https://[your-username].github.io/[repository-name]`

## Customization

### Instagram Feed
To add your Instagram feed, you can use one of these free services:
- [Elfsight Instagram Feed](https://elfsight.com/instagram-feed-widget/)
- [LightWidget](https://lightwidget.com/)
- [SnapWidget](https://snapwidget.com/)

After creating your Instagram widget, replace the placeholder in `index.html` with the embed code provided by the service.

### Email Button
Update the email address in the `mailto:` link in `index.html`:
```html
<a href="mailto:your@email.com" class="btn email-btn">
```

### Google Review Link
Replace `[YOUR_GOOGLE_BUSINESS_ID]` in the review button link with your actual Google Business ID:
```html
<a href="https://g.page/r/[YOUR_GOOGLE_BUSINESS_ID]/review" target="_blank" class="btn review-btn">
```

## Customizing Content
- Update the business description in the hero section
- Modify colors in `styles.css` to match your brand
- Add or remove sections as needed

## Development
The website is built with plain HTML and CSS, making it easy to modify and maintain. No build process is required. 