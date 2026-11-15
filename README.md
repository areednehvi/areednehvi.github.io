# areednehvi.github.io

Public home page for Arif Nazir's apps and their privacy policies, served by GitHub Pages at
https://areednehvi.github.io/

| Page | URL |
| --- | --- |
| All apps | https://areednehvi.github.io/ |
| BotCraft privacy policy | https://areednehvi.github.io/botcraft/privacy/ |

## Adding a new app

1. Copy the `botcraft/` folder to a new folder named after the app (lowercase, no spaces),
   for example `myapp/`.
2. Replace `myapp/icon.png` with the app's 512×512 icon.
3. Edit `myapp/privacy/index.html`: app name, the "Last updated" date, and each section so it
   matches what the app really does (data, ads, permissions).
4. Add an app card to `index.html` (copy the BotCraft `<article class="app-card">` block).
5. Commit and push. The policy goes live at `https://areednehvi.github.io/myapp/privacy/`
   within a minute or two; paste that link into Google Play Console and App Store Connect.

When an app is published, replace its "coming soon" text on the home page with the store link.

All pages share `assets/style.css` (light and dark mode, phone-friendly).
