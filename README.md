# Mech Force — GitHub Pages source

Publishable contents of the public site that hosts the Mech Force
**privacy policy** and **support page** (Apple requires both URLs in the
App Store Connect listing). Same structure as the Space Force site in
`docs/store/github-pages-source/`, re-skinned with Mech's neon cyan accent and the
Mech app icon.

Publish it as its own public repo named `mech-force-support` with GitHub
Pages enabled (Settings → Pages → Deploy from branch → `main` / root). URLs:

- Marketing: https://ryan-evans-git.github.io/mech-force-support/
- Support:   https://ryan-evans-git.github.io/mech-force-support/support.html
- Privacy:   https://ryan-evans-git.github.io/mech-force-support/privacy.html

`favicon.png` and `apple-touch-icon.png` are downscaled from
`projects/mech-force/assets/icon-only.png` (re-run `tools/mech-icon-gen.js`
and re-export with `sips -Z 32` / `sips -Z 180` if the icon changes).
