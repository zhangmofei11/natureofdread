# Nature of Dread Wiki

A fan-made wiki site for the horror game "Nature of Dread".

## Live Site
https://natureofdread.site

## Cloudflare Deployment

### Option 1: Cloudflare Pages (Recommended)
```bash
# Install wrangler if needed
npm install -g wrangler

# Login to Cloudflare
wrangler login

# Deploy using Pages
wrangler pages deploy . --project-name=natureofdread
```

### Option 2: Cloudflare Workers with Static Sites
```bash
wrangler deploy
```

## Local Development
Simply open `index.html` in a browser, or use a local server:
```bash
npx serve .
```

## Pages
- `index.html` - Homepage with game overview and features
- `creatures.html` - Creature bestiary and enemy guide
- `story.html` - Story/lore guide and walkthrough
- `tips.html` - Survival tips and avoidance strategies

## Customization
- Update GA4 tracking ID in each HTML file (replace `G-XXXXXXXXXX`)
- Modify Tailwind colors in the config section
