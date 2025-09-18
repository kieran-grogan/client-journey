# Paw Hootz Client Journeys

A single-page static site that renders the Paw Hootz new and returning client journey flowcharts using Mermaid.js. Built for zero-build deployment on Vercel.

## Update the Mermaid Diagrams
1. Open `index.html` in your editor.
2. Replace the content within `<pre class="mermaid" id="new-client">` with your updated Mermaid definition for the new client journey.
3. Replace the content within `<pre class="mermaid" id="returning-client">` with your updated Mermaid definition for the returning client journey.
4. Save the file and refresh the browser to see the changes locally.

## Local Preview
Simply open `index.html` in any modern browser. Mermaid renders directly in the browser via the CDN.

## Deployment on Vercel
1. Push this repository to GitHub.
2. In Vercel, import the repository and choose **Framework Preset: Other**.
3. Leave the build command blank and the output directory as `.`.
4. Deploy — Vercel will serve `index.html` as the entry point.

## Troubleshooting
- **Diagrams not rendering?** Open the browser console to check for errors and ensure `https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.min.js` is reachable.
- **Copy button not working?** Clipboard access requires a secure context (HTTPS or `localhost`). Test the feature on a secure origin.
- **Dark mode not updating?** Mermaid picks up the theme on page load. Reload the page after changing your system theme if necessary.
