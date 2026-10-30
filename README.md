# Celeste · Los Angeles

A standalone, mobile-friendly itinerary for the DLN Design Summit, November 3–7, 2026.

## Files

- `index.html` — the complete website: layout, itinerary data, styles, and interactions.
- `.nojekyll` — lets GitHub Pages serve these static files directly.

No installation, build step, API keys, external libraries, or ChatGPT account is needed to view this copy. Open `index.html` in a browser to preview it. The itinerary and interactions work offline; maps, email, and DLN portal links need an internet connection. The DLN portal requires its own sign-in.

## Publish with GitHub Pages

1. Extract this ZIP on your computer.
2. Create a GitHub repository, for example `celeste-la-itinerary`. A public repository is the simplest option for GitHub Pages.
3. In the repository, choose **Add file → Upload files**. Upload `index.html`, `.nojekyll`, and this README into the repository's top level, then commit the changes. Upload the extracted files, not the ZIP or an enclosing folder.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select your default branch (usually `main`) and **/ (root)**, then choose **Save**.
7. Wait for publishing to complete. GitHub displays the exact website link in **Settings → Pages**. Open it to check the itinerary, then share that link with Celeste.

The usual project address is `https://YOUR-USERNAME.github.io/celeste-la-itinerary/`; use the actual link GitHub provides. Standard GitHub Pages sites are publicly accessible. Choose a repository and publishing arrangement appropriate for the itinerary's contents.

GitHub's guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Use the itinerary

- Tap a date to switch days.
- Tap **See stops & details** to expand tour information.
- Use **A+** for larger text.
- Tap **Open map** for a venue search in Google Maps.
- Use **Print trip** to print all five days or save them as a PDF using the browser's print dialog.

## Update the itinerary

Edit the `days` array inside the `<script>` section of `index.html`, then upload/commit the updated file. GitHub Pages republishes after the change. This is a static snapshot, not a live connection to Outlook or DLN.

Verified on October 30, 2026. Flight, hotel, airport-transfer, and some dinner details remain pending. Saturday's Community Service Day is excluded from activities to attend because Celeste withdrew by email; the remaining portal entry is flagged for EA follow-up.
