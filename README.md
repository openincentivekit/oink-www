# https://openincentivekit.com/

Website source for the homepage for the Open INcentive Kit.


## Building

This site is based on [Hugo](https://gohugo.io/), please follow their directions to get Hugo installed first.

OINK uses submodules for theming, so you'll need to run `git submodule init && git submodule update` once when you first clone.

Once installed, you should be able to run `hugo server` (or often `hugo server --buildDrafts`) to see the site locally.


## Deploying

OINK is hosted by [Netlify](https://www.netlify.com/) and will automatically build and deploy on pushes to the `master` branch.
