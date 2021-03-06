# code.osteele.com site

The source to [code.osteele.com](https://code.osteele.com).

## Setup

1. [Install Jekyll](https://jekyllrb.com/docs/installation/)
2. Install yarn: `npm install -g yarn`
3. `bundle install` to install Ruby gems.

## Run

`yarn build` updates the list of repos, builds the Elm app, and runs Jekyll.

`yarn dev` runs the jekyll server.

## Deploy

`yarn deploy` deploys to Netlify.

## Elm Development

Install:

1. Install [foreman](https://github.com/ddollar/foreman) or one of its
   [ports](https://github.com/ddollar/foreman#ports). On macOS: `brew install forego`
2. Install [entr](http://www.entrproject.org). On macOS: `brew install entr`.

Run:

1. Run foreman or a port. E.g. `foreman start` or `forego start`.
2. Browse to [localhost:4000](http://localhost:4000)
