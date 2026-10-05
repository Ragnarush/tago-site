# tago-site

Presentation site and guide for TAGO, served by GitHub Pages at
<https://tagoapp.ca/>. French at the root, English in `en/`.

Legal documents (privacy policy, terms) live in the separate
[`legal`](https://github.com/Ragnarush/legal) repository, served at
<https://ragnarush.github.io/legal/tago/>.

Plain HTML and CSS only: no build step, no JavaScript, no external fonts, no
analytics. Every page sets a Content-Security-Policy that only allows its own
styles and images.

The section and question `id`s in `guide.html` and `en/guide.html` are linked
from the app's in-app help: keep them stable and identical in both languages.
