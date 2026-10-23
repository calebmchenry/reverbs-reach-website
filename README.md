# Reverb’s Reach

The download landing page for Reverb’s Reach, an MMORPG in development.

The site is plain HTML and CSS in `public/`. It has no JavaScript, build step, or package dependencies. Fonts are served locally; their licenses are included in `public/assets/fonts/`.

## Local preview

From the repository root:

```sh
python3 -m http.server 8000 --bind 127.0.0.1 --directory public
```

Open <http://127.0.0.1:8000>.

## Hosting

Serve `public/` as the site's document root. With a static hosting provider, leave the build command empty and set the output directory to `public`.

## Downloads

Both client buttons are disabled and labeled “Coming soon.” When releases are ready, replace the buttons in `public/index.html` with links to the hosted installers, preserving the `download` classes. Update the button labels, release status, and page metadata at the same time.

Keep installer binaries in separate release storage rather than this repository. The website and game servers can be deployed independently.

The original design explorations are retained locally in the ignored `output/` directory.
