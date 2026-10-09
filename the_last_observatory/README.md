# THE LAST OBSERVATORY

A self-contained, mobile-friendly puzzle website. No framework, build step, external fonts, or server-side code required.

## Run locally

Open `index.html` in a modern browser. On some phones, the easiest way to test is to upload the file to a static host first.

## Puzzle answer key (keep private if sharing the game)

1. `20 08 05 / 15 02 19 05 18 22 05 18` uses A1Z26 (A=1, ..., Z=26): `THE / OBSERVER`. Enter `OBSERVER`.
2. The five 8-bit ASCII groups decode to `LIGHT`. Enter `LIGHT`.
3. Sort the word fragments by their number and take the first letter: `1 Trace, 2 Return, 3 Astral, 4 Voyager, 5 Ember, 6 Light, 7 Echo, 8 Remember, 9 Silence` = `TRAVELERS`. Enter `TRAVELERS`.
4. Reverse `kGRqCKne43z` to get `z34enKCqRGk`. Enter that exact identifier. The final record opens a dedicated message page. Press **Begin transmission** to start the embedded Travelers video and reveal the message line by line. The player stays on the page after the text finishes and is configured to loop; playback behavior can still depend on YouTube and browser settings.

The small star button at the bottom-right reveals an optional hidden archive note.

## Publish free with GitHub Pages

1. Create a new repository on GitHub. For a public site on GitHub Free, the repository needs to be public.
2. Upload `index.html` to the repository root. You can include this README or leave it out of the published repo.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for the deployment and use the site URL shown in Settings → Pages. It will usually look like `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

GitHub Pages publishes static HTML directly. Published Pages sites are generally public, so do not put private information in the repository.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Notes

- The site is a client-side puzzle, not secure authentication. Answers are present in the JavaScript and can be inspected by a technically inclined visitor. This is appropriate for a casual ARG, not for protecting confidential information.
- The final soundtrack video ID is configured as `VIDEO_ID` in `index.html`. The original `TARGET` URL is retained as a reference. The embedded player needs an internet connection; press **Begin transmission** to start playback because browsers generally restrict autoplay with sound.
