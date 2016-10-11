Download any highlight theme you want to use here, e.g.:

```
$ wget https://gist.githubusercontent.com/ToastShaman/8136059/raw/abd29d4492e047e5553df95a4a9427e8c9cb323d/github.css
```

Then, edit the `pandoc.template` to include it. The section you need to change looks like this:
```
  <!-- Code syntax highlighting -->
  <link rel="stylesheet" href="$revealjs-url$/../github.css"/>
```

So, if you've downloaded a syntax theme called `red.css`, just change the `github.css` into `red.css`.
