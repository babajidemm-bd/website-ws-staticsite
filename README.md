# website-ws-staticsite
Repo to manage simple static page hosted by Github Pages.

This webpage is used as entry point for `proxy` service that will prove that proxy can handle requests to show static content and load assets.

### Assets:

- remote: css library https://daneden.github.io/animate.css/
- local: image http://dev.betterdoc.org/website-ws-staticsite/borg.gif

### Things to watch out

    Github Pages deploys the webpage when change is made on selected branch (in this repo it is `master` branch). But it does not have consisted timing for the deploy. So patience is needed in most cases.

    When adding assets note that root path is `dev.betterdoc.org/website-ws-staticsite/`. For example image `image.png` in root path of the repository would have link: `http://dev.betterdoc.org/website-ws-staticsite/image.png`.