# Hugo Breadcrumbs Module

## Setup

Add the following to your HUGO config file: 

```
[module]
  
  # Any existing modules here...

  # Install Netlify CMS
  [[module.imports]]
    path = "github.com/saderra/hugo-modules/breadcrumbs"

```

To call the breadcrums into your template, typically `partial/header.html` use the following snippet, omitting the "if" conditional if you'd also like the modules to show up on your homepage.

```
{{ if not .IsHome }}
  {{ partial "components/breadcrumb" . }}
{{ end }}
```
