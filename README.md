# The Staffing Call

A three-minute, self-guided decision exercise for senior leaders, adapted from Judgment Lab 1 (The Staffing Recommendation) in Golden Key Group's Leading with AI program.

Everything runs in the browser from a single `index.html`. Nothing is saved or sent anywhere.

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `staffing-call`.
2. Upload every file in this folder to the root of the repository, including `.nojekyll`.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
5. After a minute or two, the site is live at `https://USERNAME.github.io/staffing-call/`.

## Make link previews show the image

Text messages, Slack, Teams and LinkedIn need a full address for the preview image. In `index.html`, replace

    <meta property="og:image" content="og-image.png">

with your live address, for example

    <meta property="og:image" content="https://USERNAME.github.io/staffing-call/og-image.png">

## Files

- `index.html`: the whole exercise (styles and script included)
- `og-image.png`: 1200 x 630 link-preview image
- `.nojekyll`: tells GitHub Pages to serve the files as-is
