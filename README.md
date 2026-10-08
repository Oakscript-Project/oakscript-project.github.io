# OakScript website

Static website prepared for GitHub Pages. No build system, server-side code,
tracking, external fonts, or paid service is required.

To preview locally, run `python -m http.server 8765` from this folder and open
http://localhost:8765. The examples need the OakScript Windows runner; the browser
does not execute Oak code.

Organization: https://github.com/Oakscript-Project
Website repository: https://github.com/Oakscript-Project/oakscript-project.github.io
Website address: https://oakscript-project.github.io/

GitHub Pages publishes the `main` branch, `/ (root)`. The `.nojekyll` file keeps
the site static. No GitHub Actions workflow or separate build step is needed.

The downloads contain the verified local OakScript 0.7.0 runner and Oak Blocks
example. Keep their bundled licenses/notices. Links to the existing official
repository are retained; no repository transfer or release publication is implied.

The local links, download archives, JavaScript syntax, and runnable Oak examples
have been checked. Browser visual/interaction verification remains unavailable
because no browser is connected. Publication evidence is recorded separately
in the OakScript workspace under `artifacts/website/publication.json`.
