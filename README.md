# Buddha Chat support website

Static privacy, support, and beta-use pages for the iOS app. No forms, analytics,
cookies set by application code, runtime secrets, or JavaScript dependencies.

Published with GitHub Pages from the root of `main`:
https://forestoceanlife.github.io/buddha-chat-support/ (pushing to `main` publishes).
Links between pages are relative so the site works under that `/buddha-chat-support/`
path; `404.html` is served at any depth, so its links spell out `/buddha-chat-support/`.
The app, App Store Connect, and the main repository link to the privacy and support
pages, so keep their paths stable.

Preview with `python3 -m http.server 8876 --bind 127.0.0.1` from this folder.
The website is separate from the Supabase app service and never receives chat history.

The owner confirmed Ming Chieh Lin as operator and forestoceanlife@gmail.com as support/privacy contact on October 18, 2026. Keep the current beta scope and
provider retention statements aligned with the service. Do not advertise the
unreleased all-age experience or a reviewed teaching catalog.
