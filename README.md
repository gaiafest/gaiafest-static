# Gaia Fest Static

## How To Build Bulma CSS

Using `npm run <command>`:

- `css-build` takes sass/mystyles.scss as an input, and outputs css/mystyles.css, while omitting the source map
- `css-watch` builds the CSS and watches for changes
- `start` is simply a shortcut for css-watch

## How To Build index.html

- place your Markdown source in `content.md`
- `npm run showdown` converts `content.md` to `content.html`
- by hand, insert `content.md` into `index.html` between the `content.md` markers
