# Tournament & Bracket Maker - Support Website

Support page for Tournament & Bracket Maker app, required for App Store Connect.

## Deployment Options

### Option A: Deploy from this repository

1. Push changes to GitHub
2. Go to repository **Settings** → **Pages**
3. Source: Deploy from branch
4. Branch: `main` (or your branch), folder: `/docs/website`
5. Save and wait for deployment

**URL**: `https://<username>.github.io/champify-kmp-ios/`

### Option B: Separate repository (cleaner URL)

1. Create a new repository named `champify-support`
2. Copy the contents of this `docs/website/` folder to the new repo root
3. Enable GitHub Pages from `main` branch root
4. **URL**: `https://<username>.github.io/champify-support/`

## App Store Connect URLs

| Field | URL |
|-------|-----|
| **Support URL** | `https://<username>.github.io/champify-support/` |
| **Privacy Policy URL** | `https://sites.google.com/view/champifytournamentmaker/home` |

## Files

- `index.html` - Main support page
- `css/style.css` - Responsive styles
- `images/app-icon.png` - App icon (512px)

## Testing

Before submitting to App Store:

1. Open on iPhone Safari - verify text is readable without zooming
2. Tap email link - verify mail app opens
3. Test Privacy Policy and Terms links
