---
title       : College admission predictor tool  
subtitle    : December 21, 2014  
author      : Karl Goran Strangmark   
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [disqus]      # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Worrying about college admission?

- Dreaming about being admitted to a top college but uncertain if you have a chance to be admitted?

- Use this simple tool to figure out your chances to enter "Greedy College" next fall.

- Greedy College is using big data with an eye on maximizing its endowment fund.

- Use this super cool app and figure out your chances before you spend time and money on your application.

---

## How it works?

- Go to https://goran371.shinyapps.io/devDataProdProj/ and fill in some information about yourself and your family.

- Hit the "Go!" button and this awesome analytical tool will immediately return a prediction whether you have a chance to be admitted or not.

---

## The details

- The most important information is the zip code. Please fill it in as a 4 or 5 digit number. You may try to hit Go! to see if the zip code alone takes you to Greedy College. For about 100 superzips Greedy will admit you without any other question.

- If you don't live in a superzip, you many be able to qualify as a likely future wealthy and generous alumnus or alumna. You do that by answering the 2 questions about your family's current aggregate gross income (AGI)  and checking your father's alumnus status. Please use the value from the last taxation year (see below).

```
## [1] "2014"
```

---

## Superzips

<!-- GeoMap generated in R 3.1.2 by googleVis 0.5.6 package -->
<!-- Sun Dec 21 12:23:01 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoMapID504c27cd6040 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 42.088128,
-87.716,
1,
"Kenilworth" 
],
[
 42.130976,
-87.76252,
2,
"Glencoe" 
],
[
 40.73915,
-74.32749,
3,
"Short Hills" 
],
[
 37.458615,
-122.20009,
4,
"Atherton" 
],
[
 41.167455,
-73.77597,
5,
"Chappaqua" 
],
[
 40.042444,
-75.28002,
6,
"Gladwyne" 
],
[
 37.374421,
-122.213,
7,
"Portola Valley" 
],
[
 33.016492,
-117.20264,
8,
"Rancho Santa Fe" 
],
[
 42.358663,
-71.28831,
9,
"Weston" 
],
[
 41.037203,
-73.71588,
10,
"Purchase" 
],
[
 33.86427,
-84.41972,
11,
"Atlanta" 
],
[
 40.038477,
-75.3473,
12,
"Villanova" 
],
[
 42.357903,
-71.06408,
13,
"Boston" 
],
[
 40.827499,
-74.28091,
14,
"Essex Fells" 
],
[
 40.787368,
-73.60119,
15,
"Old Westbury" 
],
[
 41.150146,
-73.49178,
16,
"New Canaan" 
],
[
 41.269072,
-73.60493,
17,
"Cross River" 
],
[
 34.036759,
-118.50121,
18,
"Santa Monica" 
],
[
 41.075663,
-73.48294,
19,
"Darien" 
],
[
 26.759514,
-82.26351,
20,
"Boca Grande" 
],
[
 34.101007,
-118.45077,
21,
"Los Angeles" 
],
[
 40.769334,
-73.94893,
22,
"New York" 
],
[
 40.775477,
-73.9905,
23,
"New York" 
],
[
 42.104127,
-87.75016,
24,
"Winnetka" 
],
[
 42.325247,
-71.2319,
25,
"Waban" 
],
[
 42.238087,
-87.86093,
26,
"Lake Forest" 
],
[
 41.212954,
-73.58409,
27,
"Pound Ridge" 
],
[
 41.216454,
-73.37308,
28,
"Weston" 
],
[
 37.37714,
-122.12412,
29,
"Los Altos" 
],
[
 42.23888,
-71.28241,
30,
"Dover" 
],
[
 41.195778,
-73.62777,
31,
"Bedford" 
],
[
 38.546306,
-121.68682,
32,
"El Macero" 
],
[
 39.003809,
-77.30165,
33,
"Great Falls" 
],
[
 30.359935,
-97.83125,
34,
"Austin" 
],
[
 34.050505,
-118.53374,
35,
"Pacific Palisades" 
],
[
 40.696601,
-74.63781,
36,
"Far Hills" 
],
[
 40.892021,
-74.44022,
37,
"Mountain Lakes" 
],
[
 40.776777,
-73.9541,
38,
"New York" 
],
[
 42.5286,
-71.35084,
39,
"Carlisle" 
],
[
 41.201446,
-73.43758,
40,
"Wilton" 
],
[
 29.717529,
-95.42821,
41,
"Houston" 
],
[
 40.759015,
-73.96732,
42,
"New York" 
],
[
 32.862876,
-96.7904,
43,
"Dallas" 
],
[
 33.610717,
-117.8325,
44,
"Newport Coast" 
],
[
 35.197643,
-80.82752,
45,
"Charlotte" 
],
[
 40.76842,
-73.96045,
46,
"New York" 
],
[
 37.443688,
-122.15071,
47,
"Palo Alto" 
],
[
 41.146297,
-73.83311,
48,
"Briarcliff Manor" 
],
[
 38.958377,
-77.11425,
49,
"Bethesda" 
],
[
 39.035028,
-77.19995,
50,
"Potomac" 
],
[
 40.933089,
-73.75615,
51,
"Larchmont" 
],
[
 38.645802,
-90.37687,
52,
"Saint Louis" 
],
[
 32.836094,
-96.79524,
53,
"Dallas" 
],
[
 47.626571,
-122.2328,
54,
"Medina" 
],
[
 40.98845,
-73.79716,
55,
"Scarsdale" 
],
[
 41.066196,
-73.43819,
56,
"Norwalk" 
],
[
 41.140896,
-73.35178,
57,
"Westport" 
],
[
 37.270543,
-122.02305,
58,
"Saratoga" 
],
[
 42.313329,
-71.27649,
59,
"Wellesley Hills" 
],
[
 38.97511,
-77.15928,
60,
"Cabin John" 
],
[
 37.228594,
-121.98396,
61,
"Los Gatos" 
],
[
 38.93276,
-77.1677,
62,
"McLean" 
],
[
 37.353741,
-122.08717,
63,
"Los Altos" 
],
[
 38.913961,
-77.07179,
64,
"Washington" 
],
[
 40.707467,
-74.0178,
65,
"New York" 
],
[
 40.793839,
-73.65156,
66,
"Roslyn" 
],
[
 38.94081,
-77.08723,
67,
"Washington" 
],
[
 40.844199,
-74.20218,
68,
"Montclair" 
],
[
 38.97986,
-77.08079,
69,
"Chevy Chase" 
],
[
 41.033347,
-73.56804,
70,
"Old Greenwich" 
],
[
 42.34713,
-71.08234,
71,
"Boston" 
],
[
 41.532584,
-81.41052,
72,
"Gates Mills" 
],
[
 40.292358,
-74.60902,
73,
"Princeton Junction" 
],
[
 42.425537,
-71.30316,
74,
"Lincoln" 
],
[
 37.856683,
-122.02488,
75,
"Alamo" 
],
[
 42.231025,
-71.37202,
76,
"Sherborn" 
],
[
 40.786387,
-73.97709,
77,
"New York" 
],
[
 38.88619,
-77.32402,
78,
"Oakton" 
],
[
 37.892476,
-122.47541,
79,
"Belvedere Tiburon" 
],
[
 41.922682,
-87.65432,
80,
"Chicago" 
],
[
 37.804064,
-121.91202,
81,
"Danville" 
],
[
 40.410155,
-74.70726,
82,
"Skillman" 
],
[
 41.001695,
-74.10239,
83,
"Ho Ho Kus" 
],
[
 40.946805,
-73.78797,
84,
"Wykagyl" 
],
[
 38.996842,
-77.13519,
85,
"Bethesda" 
],
[
 37.878625,
-122.18296,
86,
"Orinda" 
],
[
 40.796752,
-73.68935,
87,
"Manhasset" 
],
[
 38.934866,
-77.06039,
88,
"Washington" 
],
[
 41.886456,
-87.62325,
89,
"Chicago" 
],
[
 37.801028,
-122.43836,
90,
"San Francisco" 
],
[
 38.760747,
-77.31684,
91,
"Fairfax Station" 
],
[
 41.199502,
-73.79269,
92,
"Millwood" 
],
[
 40.699226,
-74.04118,
93,
"New York" 
],
[
 34.067409,
-118.47528,
94,
"Los Angeles" 
],
[
 40.782767,
-74.59529,
95,
"Mendham" 
],
[
 33.544596,
-111.95645,
96,
"Paradise Valley" 
],
[
 34.088808,
-118.40612,
97,
"Beverly Hills" 
],
[
 38.922478,
-77.2566,
98,
"Vienna" 
],
[
 38.646981,
-90.63155,
99,
"Chesterfield" 
],
[
 40.714754,
-74.00721,
100,
"New York" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('number','rank');
data.addColumn('string','city');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoMapID504c27cd6040() {
var data = gvisDataGeoMapID504c27cd6040();
var options = {};
options["dataMode"] = "markers";
options["width"] =    556;
options["height"] =    350;
options["region"] = "US";
options["colors"] = [0xFF8747, 0xFFB581, 0xc06000];

    var chart = new google.visualization.GeoMap(
    document.getElementById('GeoMapID504c27cd6040')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geomap";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoMapID504c27cd6040);
})();
function displayChartGeoMapID504c27cd6040() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoMapID504c27cd6040"></script>
 
<!-- divChart -->
  
<div id="GeoMapID504c27cd6040" 
  style="width: 556; height: 350;">
</div>

- Data compiled for Coming Apart: The State of White America, 1960-2010 by Charles Murray (Crown Forum, 2012).  
- Excludes zip codes for post offices.  
- Four-digit zip codes have an implied zero in front of them.  
- Data from the 2000 census (meaning that income data are for calendar 1999)  

