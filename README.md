# DuoTone Syntax

> Note: This theme isn't published. It serves as the master template for all DuoTone themes.

A double-hue syntax theme for Atom.

DuoTone themes use only 2 hues (7 shades in total). It __tones down__ less important parts (like punctuation and brackets) and highlights only the __important__ ones. This leads to a more calm color scheme, but still lets you find the stuff you're looking for.

### Currently tested and optimized for these languages:

- C
- Clojure
- CoffeeScript
- C#
- CSS
- GF Markdown
- Go
- Haskell
- HTML
- Java
- JavaScript
- JSON
- Less
- Perl
- PHP
- Python
- Ruby
- SASS
- SCSS
- Stylus
- (La-)TeX
- XML
- YAML

More optimization to come..


## Create your own DuoTone theme

Here a guide how to create your own DuoTone version.

1. Clone this repo.
2. Rename it (folder, package.json, etc).
3. Change the colors in `styles/colors.less`.
4. Publish!


## Keep your DuoTone theme up to date

You can always watch this repo to get notified about changes and apply them to your theme.

Or once in while, just pull the latest version of this repo and drop it onto your theme. Then commit everything except

- `styles/colors.less`
- `LICENSE`
- `package.json`
- `README.md`

Of course, if you make changes to one of the other files (like `styles/syntax-variables.less`) it will be overridden. So you might wanna make a note which files got customized. Or submitting an issue/PR to this Repo is always welcomed if it's something that could be improved for all DuoTone themes.
