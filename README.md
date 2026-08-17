# The Never-Asked — ADC 2026 poster (paper 880)

Landing page for poster 880, IDF-WPR & ADC & Metabolic Diseases Congress 2026,
Melbourne Convention and Exhibition Centre, 19–21 August 2026.

Hare K, McAuley S, Trawley S. *The Never-Asked: Understanding the Gap in Emotional
Health Support for People Living with Diabetes in Australia.*

## Contents

| File | What it is |
|---|---|
| `index.html` | The landing page the poster's QR code points at |
| `poster_880.pdf` | The A0 poster, live text, no raster |

## Publishing this to GitHub Pages

1. Create a new **public** repo — private repos need GitHub Pro for Pages.
   Keep the name short; it ends up in the URL and a shorter URL makes a sparser,
   easier-to-scan QR code. Something like `never-asked` works.
2. **Add file → Upload files**, drag in `index.html` and `poster_880.pdf`, commit.
3. **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`, Save.
4. Wait about a minute. The URL will be `https://<username>.github.io/<repo>/`.
5. Test it on a phone with wifi off and no GitHub login — it must open for a stranger.

Then send the URL back to be encoded into the poster's QR code.

## Why not OneDrive

University OneDrive tenants commonly block anonymous external sharing, so the link
works for you and fails for everyone at the congress. GitHub Pages has no login wall,
no link expiry, and the page can be updated later — adding the DOI once the paper is
published, for instance — without reprinting the poster or changing the QR code.

## Updating the numbers

Everything on this page is drawn from the analysis in `../FINAL/`. If the manuscript
numbers move during revision, update `index.html` and the poster together.
