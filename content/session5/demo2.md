+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Speed Bumps"
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
  color = "#f1f5fd"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
 # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
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


At the end of this week, you will be able to: 
1. Explain the advantages and disadvantages of speed bumps.
1. Weigh the advantages and risks of dark liquidity.
1. Compare the key features that distinguish dark markets from lit exchanges.
1. Evaluate when a dark market would be preferred over a lit market for a particular client, asset, or situation.
 
</br></br>




<p>A ‘speed bump’ is a mechanism for slowing down fast traders in order to give slower traders a fairer chance at the market. By implementing a timed delay (usually milliseconds) between the receipt of an order and the execution of its instructions, speed bumps are intended to mitigate the effects of asymmetric information by reducing the speed advantage of fast, sophisticated traders - such as predatory high-frequency traders (IIROC,  2018). However, critics of the mechanism (including many electronic trading firms) attest that speed bumps may make markets unnecessarily complex and unfairly favor certain market participants (Osipovich, 2019). Despite these concerns, nearly a dozen exchanges have proposed or implemented speed bumps. While the design of speed bumps differs across exchanges, all speed bumps in operation (except for IEX, which employs a “symmetrical” speed bump across all but pegged orders) are random and asymmetric, meaning that only liquidity-taking order types are delayed (Aoyagi, 2020).</p>

</br>

**References** </br>
1. Aoygi, J. (2020, July 30). The Optimal Speed to Go over Speed Bumps in Financial
Markets. Retrieved on August 31, 2020 from [https://www.researchgate.net/publication/330132515_The_Dark_Side_of_Regulating_Fast_Informed_Trading](https://www.researchgate.net/publication/330132515_The_Dark_Side_of_Regulating_Fast_Informed_Trading)
1. Investment Industry Regulatory Organization of Canada (IIROC). (2018, January 28). Speed Segmentation on exchanges: competition for slow flow. Retrieved on August 21, 2020 from [https://www.iiroc.ca/Documents/2018/25d5b306-3420-43cc-b260-a1527b82bfc3_en.pdf](https://www.iiroc.ca/Documents/2018/25d5b306-3420-43cc-b260-a1527b82bfc3_en.pdf)
1. Osipovich, A. (2019, July 29). More Exchanges Add ‘Speed Bumps,’ Defying High-Frequency Traders. The Wall Street Journal. Retrieved on August 31, 2020 from [https://www.wsj.com/articles/more-exchanges-add-speed-bumps-defying-high-frequency-traders-11564401611](https://www.wsj.com/articles/more-exchanges-add-speed-bumps-defying-high-frequency-traders-11564401611)

<h3>Watch the following video</h3>
{{< youtube M6IoYrahQ24 >}}
