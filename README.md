# Deployment Checklist
The checklist we run a project through before going live.


## 1. Browsers
- [ ] Desktop: test on latest versions of Chrome, IE/Edge, Firefox, and Safari
- [ ] Mobile: test on latest versions of Mobile Safari, Mobile Chrome, and Android

## Scripts
- [ ] Remove all `console.log` lines in scripts
- [ ] Check for console errors

## Meta
- [ ] Check page titles / descriptions
- [ ] Test Facebook sharing. Provide og-tags if needed
- [ ] Does Favicon load? Pin the tab in Safari to check pinned icon

## Analytics
- [ ] Install Google Analytics and ensure it's only loaded in production

## Google Search Console
- [ ] Submit the site on Google Search Console (use Domain property type where applicable)
- [ ] Submit `sitemap.xml`

## SSL
- [ ] Install Let's Encrypt certificate
- [ ] Redirect `non-www` to `www` address (unless otherwise is required by the project)
- [ ] Redirect `http` traffic to `https`

## Github
- [ ] Remove `develop` branch or other stale branches 

# Credits
Many bits of this checklist are inspired from [Spatie's Checklist Going Live](https://github.com/spatie/checklist-going-live).

