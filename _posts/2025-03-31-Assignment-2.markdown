---
layout: post
title:  "Assignment 2"
date:   2025-03-31 23:50:48 +0100
categories: jekyll update
---
California penal code defines vandalism as “Maliciously damaging, destroying or defacing with graffiti or other inscribed material with respect to any real or personal property not his or her own”<sup>1</sup>. Vandalism is one of the least serious crimes being kept track of by the San Francisco police departments, however with an average cost of vandalism at 3370 $ <sup>2</sup>, it is certainly one that generates the most costs to the city officials, business owners and citizens alike. It manifests in different ways, from graffiti on public and private property to the destruction of street signs, vehicles, or storefronts. The motivations behind it is different - some people engage in vandalism as an act of protest, others out of boredom, and some simply to destruct property. Regardless of the intent, the results are costly and require significant resources to address. There are various ways of decreasing the amount of vandalism, such as sending out additional police patrols on days which are predicted to be problematic, investing in safer infrastructure like CCTV cameras or streetlamps in known hot spots, etc. 
![Image](/assets/dnb.png)

Vandalism occurs the most on Friday and Saturday in each of the PD’s. Elevated numbers of this crime occur at night, as shown on the plot. While there were some PDs with lower vandalism rates, most of the districts have a pretty consistent amount of this crime at about 3000. In most districts the vandalism happens mostly throughout the day, however in several districts the destruction of property is greater than average during the night. One of the ways to combat vandalism at night is to invest in street lamps which will make the criminals visible, known and vulnerable. The map below shows the cases of vandalism, divided into whether they occurred during daytime or nighttime. This data was obtained from sunrise-sunset.org <sup>3</sup>, and merged with the full police department dataset.

<iframe src="https://zbyslawmateo.github.io/assets/vandalism_map.html" width="100%" height="600px" style="border:none;"></iframe>

In 2018, the city of San Francisco has started changing out their old sodium lights for new LED lights. <sup>4</sup> LED lamps are directional, which means that they can illuminate each area with full power, without wasting energy on shining upwards. They are also cheaper to operate, which means that more can be placed at a lower cost to the city.  The number of vandalism cases during the nighttime has dropped significantly across all PD’s. However, because the data portrays records from 2020 to 2023 it might be skewed by general unrest in San Francisco (and other parts of the USA) during this period. <sup>5</sup> <sup>6</sup>

<iframe src="https://zbyslawmateo.github.io/assets/bokeh_plot.html" width="100%" height="600px" style="border:none;"></iframe>

Citations

1.	https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?sectionNum=594.&lawCode=PEN
2.	https://smallbusiness.chron.com/can-vandalism-cost-business-63820.html
3.	https://sunrise-sunset.org
4.	https://sf.curbed.com/2017/5/18/15658330/led-streetlights-sf
5.	https://www.theguardian.com/us-news/2020/jun/20/san-francisco-statues-ulysses-s-grant-junipero-serra-francis-scott-key 
6.	https://www.cbsnews.com/sanfrancisco/news/san-francisco-officials-brace-for-george-floyd-protest-march-after-night-of-bay-area-violence/
