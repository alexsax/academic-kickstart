+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Selected Projects"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = ""
  gradient_end = ""
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<div class='col-lg-12'>

  <div class='row'>
    <div class='col-lg-2'></div>
    <div class='col-lg-8 card'>
      <a href="//consistency.epfl.ch" class="custom-card">
        <div class='mr-auto project-video'>
          <video playsinline autoplay center loop muted width="100%" height="" class="video-bg" id="video-bg" poster="https://gph.is/1Qb3vhn">
            <source src="projects/consistency.mp4" type="video/mp4" alt="HTML5 background video">
          </video> 
        </div>
      </a>
      <a class='mt-auto project-name' href='//consistency.epfl.ch'>Robust Learning via Cross-Task Consistency </a>
    </div>
  </div>
  <div class='row'>
    <div class='col-lg-1'></div>
    <div class='col-lg-3 card'>
      <a href="//taskonomy.stanford.edu" class="custom-card">
          <div class='mr-auto project-video'>
            <video playsinline autoplay center loop muted width="100%" height="" class="video-bg" id="video-bg" poster="https://gph.is/1Qb3vhn">
              <source src="projects/taskonomy.mp4" type="video/mp4" alt="HTML5 background video">
            </video> 
          </div>
      </a>
      <a class='mt-auto project-name' href="//taskonomy.stanford.edu">Taskonomy: Transfer Learning</a>
    </div>
    <div class='col-lg-4 card'>
      <a href="//perceptual.actor" class="custom-card">
          <div class='mr-auto project-video'>
            <video playsinline autoplay center loop muted width="100%" height="" class="video-bg" id="video-bg" poster="https://gph.is/1Qb3vhn">
              <source src="projects/midlevel.mp4" type="video/mp4" alt="HTML5 background video">
            </video> 
          </div>
      </a>
      <a class='mt-auto project-name'  href="//perceptual.actor">Mid-Level Vision for Robotics</a>
    </div>
    <div class='col-lg-3 card'>
      <a href="http://gibsonenv.stanford.edu" class="custom-card">
        <div class='mr-auto project-video'>
          <video playsinline autoplay center loop muted width="100%" height="" class="video-bg" id="video-bg" poster="https://gph.is/1Qb3vhn">
            <source src="projects/gibson.mp4" type="video/mp4" alt="HTML5 background video">
          </video> 
        </div>
      </a>
      <a class='mt-auto project-name' href="//gibsonenv.stanford.edu">Gibson Environment</a>
    </div>    
  </div>
</div>
<!-- -->
