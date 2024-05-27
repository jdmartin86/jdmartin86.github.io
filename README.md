
## Deploying my site
The markdown files that should be edited with changes are on the `gh-pages` branch, and the published files that GitHub Pages serves are on `master`.

This site can be built with Ruby 3.3.1 and Jekyll 4.3.3.

Commit and push changes to `gh-pages`, then run [jgd](https://github.com/yegor256/jekyll-github-deploy) to build `gh-pages` and deploy to `master`.

```
jgd -r gh-pages -b master -n bundle
```

## Testing Locally
Local changes can be tested from the top-level `jdmartin86.github.io` directory with the following.

```
bundle install
bundle exec jekyll serve
```


# tufte-jekyll theme

The blog theme is based on the github repository by Edward Tufte
[here](https://github.com/edwardtufte/tufte-css), which was originally created
by Dave Leipmann, but is now labeled under Edward Tufte's moniker. 

## Demo

A sample site with self-documenting content is available
[here](http://clayh53.github.io/tufte-jekyll/) on github pages.