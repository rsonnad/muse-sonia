# muse-sonia

Muse's own pages for https://alpacaplayhouse.com/muse/.

- Put each project in `muse/<project>/` with an `index.html`. Use relative links.
- Push to `main`. Within about 10 minutes, rsonnad/alpacapps CI copies `muse/` from this repo into the site and checks the public pages.
- Only `muse/<project>/` folders are published. Project names must be lowercase letters, digits and dashes.
- A project another Muse repo already owns is not published from here.
- Force-push and deleting `main` are blocked.

Publishing status: https://github.com/rsonnad/alpacapps/actions/workflows/bump-version-on-push.yml
