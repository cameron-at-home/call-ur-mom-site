# call-ur-mom-site

Static marketing site for [call-ur-mom.com](https://call-ur-mom.com), served by GitHub Pages.

- `index.html`: landing page (static port of the home page design from Claude Design, with its styles inline)
- `privacy.html`: privacy policy for the iOS app
- `terms.html`: terms of use for the iOS app (Apple's standard EULA plus subscription and free-trial terms)
- `colors_and_type.css`: brand color and type tokens shared by the privacy and terms pages
- `CNAME`: custom domain for GitHub Pages

No build step. Preview locally with `python3 -m http.server` and open http://localhost:8000.
