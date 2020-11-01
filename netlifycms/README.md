# Hugo Netlify CMS Module

## Setup

Add the following to your HUGO config file: 

```
[module]
  
  # Any existing modules here...

  # Install Netlify CMS
  [[module.imports]]
    path = "github.com/saderra/hugo-modules/netlifycms"

```

You'll also need to add the Netlify Identity Widget to your head JS right before the `</body>` tag. 

```
{{ partial "components/netlifycms" . }
```