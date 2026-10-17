# Mandarin Zest: "Featured in" logo belt

`mandarin-zest-featured-belt.html`: the logos slide in from the side in an
endless loop (grey, full colour on hover; full colour on phones). Hover pauses it.

Embed (Odoo Embed Code block):

```html
<iframe src="https://antoinesjc.github.io/logo-belt/mandarin-zest-featured-belt.html" title="As featured in" style="width:100%;height:150px;border:0;display:block" loading="lazy"></iframe>
```

- Use 150px with the small "As featured in" label. In a frame under 130px
  (or with `?label=0`) the label is hidden.
- To add a logo: upload a PNG with a transparent background to `logos/` and
  add a line to the LOGOS list at the bottom of the HTML file (bigger `h` for
  tall logos, smaller for wide wordmarks).
