# macrointent.com

The public site: the home page, the privacy policy (`/privacy`) and how to
delete an account (`/delete-account`). Plain HTML and one stylesheet, served by
GitHub Pages from `main` — a push is a deploy. The app itself is
app.macrointent.com (meals-web-ui).

The App Store and Play listings link to `/privacy` and `/delete-account`, and
both apps link to `/privacy`: keep those paths.

Preview with `python3 -m http.server` and open http://localhost:8000.
