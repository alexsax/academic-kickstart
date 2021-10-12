+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = ""
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

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

<div class='row justify-content-md-between'>
  <!-- <div class="col-lg-1"> -->
    <!-- <a><h1>Experience</h1></a> -->
    <!-- <a></a> -->
  <!-- </div> -->
  <!-- <div class="col-md-2"></div> -->
  <div class="col-lg-2 col-md-3 col-sm-3 col-xs-6">
      <a><h4 class="experience-title">CV</h4></a>
      <div class='cv-img'>
      <a href="cv/CV.pdf"><img style='' class="layered-paper" src="cv/CV.png"></a>
      </div>
      <!-- <img class="layered-paper" src="cv/CV.png"> -->
  </div>
  <!-- <div class="col-lg-1 col-md-0"></div> -->
  <div class="col-lg-3 col-md-4 col-sm-6 col-xs-6">
    <div>
      <h4 class="experience-title">Education</h4>
      <div style="margin:0 auto; display: table; float:center;">
          <img class='experience-logo' style="margin-left: 0px;" src=experience/berkeley_seal_and_logo.jpg>
          <img class='experience-logo' style="width:91%; margin-left: 0px;" src="experience/SUSig_Seal_Stacked_Left.png">
          <!-- <img style="height:50px;; margin-left: 10px;" src="https://www.hse.ru/data/2015/10/05/1077116051/hse.png"> -->
          <!-- <img style="; margin-left: 10px;" src="experience/umd_logo.jpg"> -->
      </div>
    </div>
    </div>
    <div class="col-lg-3 col-md-5">
    <div>
      <h4 class="experience-title">Internships and Research Positions</h4>
      <div style="margin:0 auto; display: table;"> 
          <img class='experience-logo' style="height:30px; float:left; margin-left: 10px; margin-top: 7px;" src="experience/fb_research.png">
          <img class='experience-logo'  style="height:30px; float:left; margin-left: 10px; margin-top: 7px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Microsoft_logo_%282012%29.svg/2000px-Microsoft_logo_%282012%29.svg.png">
          <img class='experience-logo' style="height:42px; float:left; margin-left: 10px;" src="experience/stanford_seal.png">
          <img class='experience-logo' style="height:35px; float:left; margin-left: 10px;; margin-top: 6px;" src="experience/RTI_logo.png">
      </div>
    </div>
  </div>
</div>