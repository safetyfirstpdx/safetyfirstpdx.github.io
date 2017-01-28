# safetyfirstpdx.github.io
PDX Tech Community Safety &amp; Accountability

View the site at [safetyfirstpdx.org](http://safetyfirstpdx.org)

A work in progress! Contact audrey@lifeofaudrey.com to get involved


## Development notes

## Developing locally

`jekyll serve --config _config.yml,_config.dev.yml --watch`

* Nav configuration lives in the `nav_items` entry in the primary jekyll config (`_config.yml`).
* CSS configuration uses SASS and lives in the `_sass` directory.
* Partials live in the `_includes` directory.

## Testing gh-pages on a fork

You can test github pages using a fork, if you push to the `gh-pages` branch
with the CNAME file removed. Be careful not to merge removal of the CNAME
record to the real project.
