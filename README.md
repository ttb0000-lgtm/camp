# BigLinker Camps — 12-language camp page

A single-page site for BigLinker Camps. Visitors first choose one of 12 languages, then see camps in Korea (world → Korea), camps abroad for Korean students (Korea → world), the K-POP Creative Summer track record and contact details. It is optimised for phones.

- `index.html` — the whole page. Photos are embedded, so this one file is all that needs hosting.
- Adding `#ja`, `#vi`, `#es` and so on to the end of the link skips the language screen and opens that language directly.

## Publishing with GitHub Pages

1. Create a repository (for example `biglinker-camps`) and upload `index.html` and this README.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute or two the page is live at `https://<your-username>.github.io/biglinker-camps/`.

GitHub Pages from a **private** repository needs a paid GitHub plan (Pro, Team or Enterprise). On the free plan the repository must be public. In both cases the published page itself is public, which is what the QR code needs.

## Editing

- Contact details: search `index.html` for `biglinkerkor@gmail.com` and `+82 2 2039 8584`.
- Wording: each language is one block inside the `T={…}` object near the bottom of `index.html`.
