+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Session 5"
subtitle = "Innovative Market Structures"

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
1. explain the advantages and disadvantages of speed bumps.
1. weigh the advantages and risks of dark liquidity.
1. compare the key features that distinguish dark markets from lit exchanges.
1. evaluate when a dark market would be preferred over a lit market for a particular client, asset, or situation.
 
</br></br>
<h2>Preview of Activities</h2>
<a class="color:#323232" href="#projects"><h3 >Quiz</h3></a>
This assessment will count towards your individual participation grade.



</br></br>
<h2>Speed Bumps</h2>
A ‘speed bump’ is a mechanism for slowing down fast traders in order to give slower traders a fairer chance at the market. By implementing a timed delay (usually milliseconds) between the receipt of an order and the execution of its instructions, speed bumps are intended to mitigate the effects of asymmetric information by reducing the speed advantage of fast, sophisticated traders - such as predatory high-frequency traders (IIROC,  2018). However, critics of the mechanism (including many electronic trading firms) attest that speed bumps may make markets unnecessarily complex and unfairly favor certain market participants (Osipovich, 2019). Despite these concerns, nearly a dozen exchanges have proposed or implemented speed bumps. While the design of speed bumps differs across exchanges, all speed bumps in operation (except for IEX, which employs a “symmetrical” speed bump across all but pegged orders) are random and asymmetric, meaning that only liquidity-taking order types are delayed (Aoyagi, 2020).

**References** 

Aoygi, J. (2020, July 30). The Optimal Speed to Go over Speed Bumps in Financial
Markets. Retrieved on August 31, 2020 from [https://www.researchgate.net/publication/330132515_The_Dark_Side_of_Regulating_Fast_Informed_Trading](https://www.researchgate.net/publication/330132515_The_Dark_Side_of_Regulating_Fast_Informed_Trading)
 
Investment Industry Regulatory Organization of Canada (IIROC). (2018, January 28). Speed Segmentation on exchanges: competition for slow flow. Retrieved on August 21, 2020 from [https://www.iiroc.ca/Documents/2018/25d5b306-3420-43cc-b260-a1527b82bfc3_en.pdf](https://www.iiroc.ca/Documents/2018/25d5b306-3420-43cc-b260-a1527b82bfc3_en.pdf)
 
Osipovich, A. (2019, July 29). More Exchanges Add ‘Speed Bumps,’ Defying High-Frequency Traders. The Wall Street Journal. Retrieved on August 31, 2020 from [https://www.wsj.com/articles/more-exchanges-add-speed-bumps-defying-high-frequency-traders-11564401611](https://www.wsj.com/articles/more-exchanges-add-speed-bumps-defying-high-frequency-traders-11564401611)

<h3>Watch the following video</h3>
{{< youtube M6IoYrahQ24 >}}

</br></br>
<h2>High-Frequency Trading</h2>

High-frequency traders use powerful computing technology to quickly process a high number of trades, often applying complex algorithms to trade across several markets simultaneously. In 2010, the SEC identified five characteristics that are frequently associated with high-frequency trading:
1. Use of extraordinarily high speed and sophisticated programs for generating, routing, and executing orders.
1. Use of co-location services and individual data feeds offered by exchanges and others to minimize network and other latencies.
1. Very short time-frames for establishing and liquidating positions.
1. Submission of numerous orders that are cancelled shortly after submission.
1. Ending the trading day in as close to a flat position as possible (that is, not carrying significant, unhedged positions overnight).” [(SEC, 2014, pg. 4)](https://www.sec.gov/marketstructure/research/hft_lit_review_march_2014.pdf)
 
High-frequency trading made notable headlines in 2010 when it was suspected to have been the driver of a “flash crash” that occurred on May 6, 2010; during the crash, a number of stock indices including the S&P 500 and the Dow Jones Industrial Average collapsed and rebounded within the span of 36 minutes. Within the 2010 Concept Release, the SEC acknowledged that HFT was one of the most significant market structure developments of the period, and that “[b]y any measure, HFT is a dominant component of the current market structure and likely to affect nearly all aspects of its performance.” [(SEC, 2010, pg. 3606)]((https://www.sec.gov/rules/concept/2010/34-61358fr.pdf))

**References**
U.S. Securities and Exchange Commission (SEC). (2010). Concept Release on Equity Market Structure; Proposed Rule. Federal Register / Vol. 75, No. 13. Retrieved on August 6, 2020 from [https://www.sec.gov/rules/concept/2010/34-61358fr.pdf](https://www.sec.gov/rules/concept/2010/34-61358fr.pdf) 
 
U.S. Securities and Exchange Commission (SEC). (2014). Equity Market Structure Literature - Review Part II: High Frequency Trading. Retrieved on August 6, 2020 from [https://www.sec.gov/marketstructure/research/hft_lit_review_march_2014.pdf](https://www.sec.gov/marketstructure/research/hft_lit_review_march_2014.pdf)

<h3>AT & HFT: Mandatory Readings</h3>
<p>As you read through the articles below, consider how computerized trading has changed the trading landscape. 
</p>

1. <h4>Getting Up to Speed on High-Frequency Trading</h4> 
FINRA Staff. (2015, November 25). [Getting Up to Speed on High-Frequency Trading](https://www.finra.org/investors/insights/getting-speed-high-frequency-trading). Retrieved on July 30, 2020 from https://www.finra.org/investors/insights/getting-speed-high-frequency-trading
1. <h4>Equity Market Structure Literature Review Part II: High Frequency Trading</h4>
**Pages 4 - 11** of U.S. Securities and Exchange Commission. (2014, March 18). [Equity Market Structure Literature Review Part II: High Frequency Trading](https://www.sec.gov/marketstructure/research/hft_lit_review_march_2014.pdf). Retrieved on July 30, 2020 from https://www.sec.gov/marketstructure/research/hft_lit_review_march_2014.pdf
1. <h4>Tapping the Brakes: Are Less Active Markets Safer and Better for the Economy?</h4>
Stiglitz, J. (2014, April 15).  [Tapping the Brakes: Are Less Active Markets Safer and Better for the Economy?](https://www8.gsb.columbia.edu/faculty/jstiglitz/sites/jstiglitz/files/2014_Tapping_Brakes_pub.pdf) Retrieved on July 30, 2020 from https://www8.gsb.columbia.edu/faculty/jstiglitz/sites/jstiglitz/files/2014_Tapping_Brakes_pub.pdf

</br></br>

<h2>Execution Benchmarks</h2>

<h3>Execution Benchmarks: Mandatory Readings</h3>
<p>Execution benchmarks are used to analyze trade performance and to make decisions about modifying algorithms. The following article presents how execution benchmarks are used to conduct a transaction-cost analysis (TCA).
</p>

1. <h4>Know Your Benchmark</h4> 
RCM Alternatives. (2018, June 28). [Know Your Benchmark](https://www.rcmalternatives.com/rcmx/2018/06/know-your-benchmark/). Retrieved August 07, 2020, from https://www.rcmalternatives.com/rcmx/2018/06/know-your-benchmark/

</br>


