+++
## Tag Cloud widget
widget = "tag_cloud"
headless = true  # This file represents a page section
active = true  # Activate this widget? true/false
weight = 120  # Order that this section will appear

title = "Popular Topics"
subtitle = ""

[content]
  ## Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy = "tags"
  
  ## Choose how many tags you would like to display (0 = all tags)
  count = 20

[design]
  ## Minimum and maximum font sizes (1.0 = 100%).
  font_size_min = 1.0
  font_size_max = 3.0
  
[design.background] 
  ## Background image
  # image = "brain_neuron.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.7  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = false  # Use a fun parallax-like fixed background effect? true (default)/false

  ### Choose a light or dark text color by setting `text_color_light`.
  # Text color (true=light or false=dark)
  text_color_light = false
+++
