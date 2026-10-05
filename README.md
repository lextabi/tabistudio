# Tabi Studio website

The official Tabi Studio website, served with GitHub Pages at https://lextabi.github.io/tabistudio/
(Pages: `main` branch, root folder). Plain HTML and CSS, no build step: edit a file, commit, push.

| Page | What's on it |
|---|---|
| `index.html` | Studio home: the apps (Runling, MT App, SyntaxDeck and Calm Crew open for testing), how testing works, about, contact |
| `runling/index.html` | Runling: screenshots, features, getting started, your data |
| `runling/changelog.html` | What's new: every Runling version for testers, with its APK's SHA-256 |
| `runling/privacy.html` | Runling privacy policy (linked from the game and Health Connect: **keep this URL**) |
| `runling/delete-account.html` | How to delete a Runling account (Play's "delete account" URL: **keep this URL**) |
| `mt-app/index.html` | MT App: screenshots, features, getting started, your data |
| `mt-app/changelog.html` | What's new: every MT App version for testers, with its APK's SHA-256 |
| `syntaxdeck/index.html` | SyntaxDeck: screenshots, features, getting started, your data (its privacy section is `syntaxdeck/#privacy`) |
| `syntaxdeck/changelog.html` | What's new: every SyntaxDeck version for testers, with its APK's SHA-256 |
| `calm-crew/index.html` | Calm Crew: screenshots, features, how it's designed to be calm, getting started, your data |
| `calm-crew/changelog.html` | What's new: every Calm Crew version for testers, with its APK's SHA-256 |
| `calm-crew/privacy.html` | Calm Crew privacy policy (**keep this URL**) |
| `style.css` | Shared styles: brand kit v1 colours (Indigo, Jade, Paper, Slate), Lexend + Instrument Sans, light and dark |

`assets/brand/` holds the logos from the brand kit (`C:\Projects\MyResources\Tabi-Studio-Brand`),
`assets/apps/` the app icons (SyntaxDeck's `syntaxdeck.svg` is the app's `syntaxdeck-icon.svg` cropped to the launcher's visible area; Calm Crew's is `calm-crew.png`, resized from the app's `icon-only.png`), and each app folder its screenshots.

**When an app gets a new version:** add the version at the top of its `changelog.html` (what changed
in tester-friendly words, the APK file name and its SHA-256), update its version in `index.html` (app
card) and on its page (badge), and swap screenshots if the look changed. Downloads stay on the Google
Drive folders. This site is the only public release page; the old `*_release` repos were retired in
October 2026. Update `runling/privacy.html` (and its date)
whenever Runling starts collecting something new.

**Calm Crew** (added 4 Oct 2026; first test version 0.3.0 on 5 Oct 2026). For each new version: add it at
the top of `calm-crew/changelog.html` (APK file name `calmcrew_<version>.apk` and its SHA-256), update the
version on its card in `index.html` and the badge on `calm-crew/index.html`, and keep `calm-crew/privacy.html`
current (update its date if the app ever collects or sends anything). The Calm Crew page is public: it describes
the app for children on the autism spectrum in general and never refers to any real child or family.
