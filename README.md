# Tabi Studio website

The official Tabi Studio website, served with GitHub Pages at https://lextabi.github.io/tabistudio/
(Pages: `main` branch, root folder). Plain HTML and CSS, no build step: edit a file, commit, push.

| Page | What's on it |
|---|---|
| `index.html` | Studio home: the apps (open testing), how testing works, about, contact |
| `runling/index.html` | Runling: screenshots, features, getting started, your data |
| `runling/privacy.html` | Runling privacy policy (linked from the game and Health Connect: **keep this URL**) |
| `runling/delete-account.html` | How to delete a Runling account (Play's "delete account" URL: **keep this URL**) |
| `mt-app/index.html` | MT App: screenshots, features, getting started, your data |
| `style.css` | Shared styles: brand kit v1 colours (Indigo, Jade, Paper, Slate), Lexend + Instrument Sans, light and dark |

`assets/brand/` holds the logos from the brand kit (`C:\Projects\MyResources\Tabi-Studio-Brand`),
`assets/apps/` the app icons, and each app folder its screenshots.

**When an app gets a new version:** update its version in `index.html` (app card) and on its page
(badge), and swap screenshots if the look changed. Downloads stay on the Google Drive folders;
each app's `*_release` repo has the full changelog. Update `runling/privacy.html` (and its date)
whenever Runling starts collecting something new.
