# Hugo Blog Tools Module

## Setup

Add the following to your HUGO config file: 

```
[module]
  
  # Any existing modules here...

  # Install Netlify CMS
  [[module.imports]]
    path = "github.com/saderra/hugo-modules/blogtools"

```

To call the tools into your template, use the following snippets:

### Blog Card

```
{{ partial "blog/card" . }}
```
