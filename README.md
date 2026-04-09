# pynw.org

The source of content for the [Python North West website](https://pynw.org/) which is built using a
static site generator called [beemo](https://github.com/bennuttall/beemo).

## Content

This repo contains content, static files and
[Chameleon](https://chameleon.readthedocs.io/en/latest/) templates for the website.

## Build

Requires [beemo](https://github.com/bennuttall/beemo) with the `logs` extra installed.

```bash
make build          # build the site
make logs           # process Apache logs into CSV
make analytics         # generate analytics report
make serve          # serve the site locally on port 8011
make serve-analytics   # serve the analytics report on port 8012
```

## Licences

Contents are Copyright Python North West. The HTML template is provide by [HTML5
Up](https://html5up.net/) licenced under [Creative Commons Attribution 3.0
Unported](http://creativecommons.org/licenses/by/3.0/)