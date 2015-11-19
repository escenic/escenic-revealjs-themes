# Escenic branded themes for reveal.js presentations

## Usage

```
$ cd my-slides
$ /path/to/escenic-revealjs-themes/bin/create-slides \
  --theme light \
  --dir /tmp/output \
  my-presentation.md
Slides available in /tmp/output/index.html
```

You can now browse the presentation with:

```
$ firefox /tmp/output/index.html &
```

## Themes

See all the available themes in the `themes` directory.

## Installation

Clone this repository:

    $ git clone git@github.com:escenic/escenic-revealjs-themes.git

You then need some common artifacts in your `common` directory:

    $ cd common
    $ git clone https://github.com/hakimel/reveal.js.git
    $ wget https://gist.githubusercontent.com/ToastShaman/8136059/raw/abd29d4492e047e5553df95a4a9427e8c9cb323d/github.css

## Copying

Please do, see [LICENSE](LICENSE) for further details.

