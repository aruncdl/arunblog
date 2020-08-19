+++
# Introduce the blog.
widget = "starter.blog.intro"
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear in.

title = "Eternal Optimist"
subtitle = "Break free from 280 characters"

{{ range .AlternativeOutputFormats -}}
    {{ printf `<link rel="%s" type="%s" href="%s" title="%s" />` .Rel .MediaType.Type .Permalink $.Site.Title | safeHTML }}
{{ end -}}

[design.background]
  # Background color.
  color = "#23252F"

  # Text color (true=light or false=dark).
  text_color_light = true

+++
