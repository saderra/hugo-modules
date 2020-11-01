# Saderra UI Starter Theme

Load the theme as a module:

```toml

[module]

  [[module.imports]]
    path = "github.com/saderra/hugo-modules/uitheme"

```


Import it into your project, and then run:

```bash
hugo mod npm pack
npm install
```

You need to add this to your `config.toml` (the stats are used by the CSS purging):

```toml
[build]
writeStats = true
```

Then run your project as usual.