+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = false  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "450px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = ""
  content = "Find my abstracts and publications on ADS Abstract Server"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  #overlay_color = "#666"  # An HTML color value.
  overlay_img = "slider/kpnosunset.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "search ads"
  cta_url = "https://ui.adsabs.harvard.edu/search/fl=identifier%2C%5Bcitations%5D%2Cabstract%2Cauthor%2Cbibcode%2Ccitation_count%2Ccomment%2Cdoi%2Cid%2Ckeyword%2Cpage%2Cproperty%2Cpub%2Cpub_raw%2Cpubdate%2Cpubnote%2Cread_count%2Ctitle%2Cvolume%2Clinks_data%2Cesources%2Cdata%2Ccitation_count_norm%2Cemail%2Cdoctype&q=(((author%3A%22cooper%2C%20olivia%22)%20AND%20year%3A2016-)%20AND%20collection%3Aastronomy)&rows=25&sort=date%20desc%2C%20bibcode%20desc&start=0&p_=0"
  cta_icon_pack = "fas"
  cta_icon = "search"

[[item]]
  title = ""
  content = "In the press, blog posts, and more"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "slider/trail.JPG"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

 # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "media"
  cta_url = "press/"
  cta_icon_pack = "fas"
  cta_icon = "newspaper"

+++
