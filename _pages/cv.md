---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

-Education
======
* Ph.D in Electrical Engineering, King Abdullah University of Science and Technology, 2021 (expected)
* M.S. in Computer Engineering, University of Chinese Academy of Sciences, 2016
* B.S. in Electrical Engineering, Beijing Forestry University, 2013

  
-Skills
======
* **Languages**: Chinese (Mother tongue), English (Fluent), German (Beginner, A2), Arabic (Quitter :joy:)
* **Programming**: MATLAB, Python (TensorFlow), C# (Unity 3D), C/C++ (Arduino), Verilog, VHDL
* **Skills**: VR/AR Development, Interactive Simulation & Visualization, 3D Modeling


-Honors & Awards
=====
* Scholarship:\
KAUST Fellowship (2016-2021)\
Chinese Academy of Sciences Excellent Undergraduate Scholarship (2013)\
National Scholarship (2‰, 2010-2013, 3 times, awarded by Ministry of Education of China)
* Honors:\
Excellent Graduate Student of Beijing (2013)\
Excellent Students Award of Beijing (2011)
* Awards:\
4th place in Microsoft Indoor Localization Competition (IPSN 2017, Pittsburgh, PA, USA)\
1st Prize in Beijing, 3rd Prize in China (iCAN Contest 2012, Wuxi, China)\
Honorable Mention (The Mathematical Contest in Modeling, 2012, USA)\
3rd Prize (National Undergraduate Electronic Design Contest, 2012, Beijing, China)

-Activities
======
* 2019.01 - Present:    Startup ‘**Nommas’ co-founder** in TAQADAM Accelerator (2019) with $ 20K grant-funding
* 2020.03 - 2020.04: **Mixed Reality (MR) Intern** at NEOM Smart City, RIyadh, KSA
* 2019.08 - 2020.06: **Residential Assistant** in the Office of Residential Life, Graduate Affairs, KAUST
* 2017.09 - 2018.12: **Teaching Assistant** in course EE241 Digital Communication and Coding, KAUST
* 2016.09 - 2018.09: **Chinese Language Teacher** in Culture & Language Exchange Group, KAUST

<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/dark.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 1000px; height: 450px;"></div>
<div style="width: 1000px; font-size: 70%; padding: 5px 0; text-align: center; background-color: #535364; margin-top: 1px; color: #B4B4B7;"><a href="https://www.amcharts.com/visited_countries/" style="color: #B4B4B7;">Create your own visited countries map</a> or check out the <a href="https://www.amcharts.com/" style="color: #B4B4B7;">JavaScript Charts</a>.</div>
<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "dark",
projection: "mercator",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "worldHigh",
getAreasFromMap : true,
areas :
[
	{
		"id": "RU",
		"showAsSelected": true
	},
	{
		"id": "GL",
		"showAsSelected": true
	},
	{
		"id": "CN",
		"showAsSelected": true
	},
	{
		"id": "SA",
		"showAsSelected": true
	}
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>
