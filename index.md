---
title       : Demo2
subtitle    : Using GoogleVis Package for data visualization
author      : William
job         : Exchange Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : solarized_light      # 
widgets     : [quiz,bootstrap,shiny,interactive]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

--- .class #id 

## Code of Chart 1

> 1. original<-read.csv("20150108.csv")
> 2. suppressPackageStartupMessages(library(googleVis))
> 3. by1<-aggregate(original$人數,by=list(original$車次,original$下車站),sum)
> 4. names(by1)<-c("Train","Station","Man")
> 5. columnOfTrainAndStation<-gvisColumnChart(by1)
> 6. plot(columnOfTrainAndStation)


```
## starting httpd help server ...
```

```
##  done
```


--- .class #id

## Column Chart of Station & Train

<!-- ColumnChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID16ff35fffdf4 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "D04",
51 
],
[
 "G04",
31 
],
[
 "G09",
46 
],
[
 "D02",
94 
],
[
 "D05",
2 
],
[
 "D06",
202 
],
[
 "D07",
16 
],
[
 "D12",
47 
],
[
 "D14",
34 
],
[
 "D18",
34 
],
[
 "G12",
223 
],
[
 "G13",
99 
],
[
 "G19",
26 
],
[
 "G24",
105 
],
[
 "G26",
32 
],
[
 "K01",
13 
],
[
 "K04",
41 
],
[
 "K07",
26 
],
[
 "K10",
22 
],
[
 "K15",
54 
],
[
 "K18",
102 
],
[
 "T01",
61 
],
[
 "D03",
305 
],
[
 "D05",
165 
],
[
 "D07",
109 
],
[
 "D09",
249 
],
[
 "D11",
161 
],
[
 "D13",
187 
],
[
 "D15",
371 
],
[
 "D17",
237 
],
[
 "D19",
148 
],
[
 "D17",
18 
],
[
 "K06",
104 
],
[
 "K12",
19 
],
[
 "G09",
97 
],
[
 "K02",
26 
],
[
 "K06",
42 
],
[
 "K08",
27 
],
[
 "D02",
366 
],
[
 "D04",
377 
],
[
 "D06",
244 
],
[
 "D08",
173 
],
[
 "D10",
116 
],
[
 "D12",
81 
],
[
 "D14",
71 
],
[
 "D16",
83 
],
[
 "D18",
47 
],
[
 "G04",
163 
],
[
 "G05",
70 
],
[
 "G06",
274 
],
[
 "G07",
102 
],
[
 "G08",
104 
],
[
 "G09",
243 
],
[
 "G10",
220 
],
[
 "G11",
63 
],
[
 "G12",
149 
],
[
 "G13",
209 
],
[
 "G14",
69 
],
[
 "G15",
79 
],
[
 "G16",
43 
],
[
 "G17",
49 
],
[
 "G18",
215 
],
[
 "G19",
33 
],
[
 "G20",
152 
],
[
 "G21",
62 
],
[
 "G22",
123 
],
[
 "G23",
126 
],
[
 "G24",
82 
],
[
 "G25",
185 
],
[
 "G26",
101 
],
[
 "G27",
40 
],
[
 "G28",
98 
],
[
 "K01",
75 
],
[
 "K03",
23 
],
[
 "K06",
168 
],
[
 "K07",
126 
],
[
 "K08",
20 
],
[
 "K10",
54 
],
[
 "K12",
17 
],
[
 "K15",
38 
],
[
 "K16",
30 
],
[
 "T01",
134 
],
[
 "Z02",
70 
],
[
 "D03",
3 
],
[
 "D10",
130 
],
[
 "D14",
66 
],
[
 "D15",
9 
],
[
 "D17",
8 
],
[
 "D18",
33 
],
[
 "D19",
1 
],
[
 "G01",
99 
],
[
 "G02",
38 
],
[
 "G03",
71 
],
[
 "G20",
96 
],
[
 "G22",
20 
],
[
 "G25",
128 
],
[
 "K02",
88 
],
[
 "K03",
12 
],
[
 "K04",
57 
],
[
 "K07",
28 
],
[
 "K11",
21 
],
[
 "K16",
21 
],
[
 "K17",
34 
],
[
 "K18",
74 
],
[
 "T01",
54 
],
[
 "D03",
5 
],
[
 "D06",
88 
],
[
 "D13",
35 
],
[
 "D17",
31 
],
[
 "G01",
53 
],
[
 "G02",
10 
],
[
 "G03",
45 
],
[
 "G05",
46 
],
[
 "G08",
97 
],
[
 "G14",
23 
],
[
 "G16",
18 
],
[
 "G17",
17 
],
[
 "G18",
46 
],
[
 "G21",
16 
],
[
 "G27",
16 
],
[
 "G28",
135 
],
[
 "K04",
57 
],
[
 "K10",
5 
],
[
 "K15",
20 
],
[
 "K16",
26 
],
[
 "T01",
13 
],
[
 "D02",
121 
],
[
 "D03",
14 
],
[
 "D04",
137 
],
[
 "D05",
32 
],
[
 "D06",
167 
],
[
 "D07",
34 
],
[
 "D08",
145 
],
[
 "D09",
74 
],
[
 "D10",
61 
],
[
 "D11",
34 
],
[
 "D12",
59 
],
[
 "D13",
22 
],
[
 "D14",
34 
],
[
 "D15",
30 
],
[
 "D16",
61 
],
[
 "D17",
60 
],
[
 "D18",
24 
],
[
 "D19",
38 
],
[
 "G01",
60 
],
[
 "G02",
23 
],
[
 "G03",
66 
],
[
 "G04",
103 
],
[
 "G05",
75 
],
[
 "G06",
93 
],
[
 "G07",
72 
],
[
 "G08",
61 
],
[
 "G09",
141 
],
[
 "G10",
194 
],
[
 "G11",
68 
],
[
 "G12",
108 
],
[
 "G13",
122 
],
[
 "G14",
52 
],
[
 "G15",
48 
],
[
 "G16",
26 
],
[
 "G17",
65 
],
[
 "G18",
143 
],
[
 "G19",
55 
],
[
 "G20",
53 
],
[
 "G21",
60 
],
[
 "G22",
52 
],
[
 "G23",
73 
],
[
 "G24",
84 
],
[
 "G25",
130 
],
[
 "G26",
26 
],
[
 "G27",
31 
],
[
 "G28",
106 
],
[
 "K01",
16 
],
[
 "K02",
41 
],
[
 "K03",
4 
],
[
 "K04",
63 
],
[
 "K06",
52 
],
[
 "K07",
19 
],
[
 "K08",
24 
],
[
 "K10",
14 
],
[
 "K11",
19 
],
[
 "K12",
10 
],
[
 "K15",
41 
],
[
 "K16",
22 
],
[
 "K17",
43 
],
[
 "K18",
34 
],
[
 "T01",
31 
],
[
 "Z02",
63 
],
[
 "D05",
28 
],
[
 "D06",
74 
],
[
 "D16",
80 
],
[
 "G04",
36 
],
[
 "G19",
86 
],
[
 "K18",
8 
],
[
 "D02",
79 
],
[
 "D03",
38 
],
[
 "D04",
128 
],
[
 "D05",
22 
],
[
 "D06",
113 
],
[
 "D07",
26 
],
[
 "D08",
55 
],
[
 "D09",
91 
],
[
 "D10",
67 
],
[
 "D11",
46 
],
[
 "D12",
73 
],
[
 "D13",
36 
],
[
 "D14",
102 
],
[
 "D15",
163 
],
[
 "D16",
56 
],
[
 "D17",
93 
],
[
 "D18",
35 
],
[
 "D19",
24 
],
[
 "G01",
21 
],
[
 "G02",
14 
],
[
 "G03",
66 
],
[
 "G04",
46 
],
[
 "G05",
44 
],
[
 "G06",
35 
],
[
 "G07",
77 
],
[
 "G08",
29 
],
[
 "G09",
73 
],
[
 "G10",
108 
],
[
 "G11",
38 
],
[
 "G12",
43 
],
[
 "G13",
90 
],
[
 "G14",
32 
],
[
 "G15",
16 
],
[
 "G16",
20 
],
[
 "G17",
58 
],
[
 "G18",
68 
],
[
 "G19",
33 
],
[
 "G20",
34 
],
[
 "G21",
47 
],
[
 "G22",
43 
],
[
 "G23",
25 
],
[
 "G24",
33 
],
[
 "G25",
142 
],
[
 "G26",
25 
],
[
 "G27",
19 
],
[
 "G28",
33 
],
[
 "K01",
5 
],
[
 "K02",
30 
],
[
 "K03",
1 
],
[
 "K04",
29 
],
[
 "K06",
23 
],
[
 "K07",
17 
],
[
 "K08",
13 
],
[
 "K10",
8 
],
[
 "K11",
14 
],
[
 "K12",
3 
],
[
 "K15",
5 
],
[
 "K16",
11 
],
[
 "K17",
9 
],
[
 "K18",
24 
],
[
 "T01",
3 
],
[
 "Z02",
45 
],
[
 "K01",
58 
] 
];
data.addColumn('string','Train');
data.addColumn('number','Man');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID16ff35fffdf4() {
var data = gvisDataColumnChartID16ff35fffdf4();
var options = {};
options["allowHtml"] = true;
options["width"] =   1000;
options["height"] =    400;

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID16ff35fffdf4')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID16ff35fffdf4);
})();
function displayChartColumnChartID16ff35fffdf4() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID16ff35fffdf4"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID16ff35fffdf4" 
  style="width: 1000; height: 400;">
</div>

--- .class #id

## Column Chart of Boarding On Station Only

Boarding On Station V.S Boarding Off Station
<!-- ColumnChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID16ff6699bb4c () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "ZD022",
69 
],
[
 "ZD062",
267 
],
[
 "ZD111-01",
9221 
],
[
 "ZD111-02",
501 
],
[
 "ZD120",
35 
],
[
 "ZD190-01",
1630 
],
[
 "ZD190-02",
311 
],
[
 "ZD192",
730 
],
[
 "ZD250",
2415 
],
[
 "ZD311",
293 
],
[
 "ZD326",
2416 
] 
];
data.addColumn('string','Station');
data.addColumn('number','Man');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID16ff6699bb4c() {
var data = gvisDataColumnChartID16ff6699bb4c();
var options = {};
options["allowHtml"] = true;
options["width"] =   1000;
options["height"] =    200;

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID16ff6699bb4c')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID16ff6699bb4c);
})();
function displayChartColumnChartID16ff6699bb4c() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID16ff6699bb4c"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID16ff6699bb4c" 
  style="width: 1000; height: 200;">
</div>
<!-- ColumnChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID16ff76d7af33 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "ZD022",
128 
],
[
 "ZD062",
1233 
],
[
 "ZD111-01",
1932 
],
[
 "ZD111-03",
18 
],
[
 "ZD120",
123 
],
[
 "ZD121",
123 
],
[
 "ZD143",
69 
],
[
 "ZD190-01",
5367 
],
[
 "ZD190-02",
1091 
],
[
 "ZD192",
802 
],
[
 "ZD250",
3833 
],
[
 "ZD311",
312 
],
[
 "ZD326",
2799 
],
[
 "ZD370",
58 
] 
];
data.addColumn('string','Station');
data.addColumn('number','Man');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID16ff76d7af33() {
var data = gvisDataColumnChartID16ff76d7af33();
var options = {};
options["allowHtml"] = true;
options["width"] =   1000;
options["height"] =    200;

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID16ff76d7af33')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID16ff76d7af33);
})();
function displayChartColumnChartID16ff76d7af33() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID16ff76d7af33"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID16ff76d7af33" 
  style="width: 1000; height: 200;">
</div>

--- .class #id

## Column Chart of Trains Only

<!-- BarChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataBarChartID16ff73015a3b () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "D02",
660 
],
[
 "D03",
365 
],
[
 "D04",
693 
],
[
 "D05",
249 
],
[
 "D06",
888 
],
[
 "D07",
185 
],
[
 "D08",
373 
],
[
 "D09",
414 
],
[
 "D10",
374 
],
[
 "D11",
241 
],
[
 "D12",
260 
],
[
 "D13",
280 
],
[
 "D14",
307 
],
[
 "D15",
573 
],
[
 "D16",
280 
],
[
 "D17",
447 
],
[
 "D18",
173 
],
[
 "D19",
211 
],
[
 "G01",
233 
],
[
 "G02",
85 
],
[
 "G03",
248 
],
[
 "G04",
379 
],
[
 "G05",
235 
],
[
 "G06",
402 
],
[
 "G07",
251 
],
[
 "G08",
291 
],
[
 "G09",
600 
],
[
 "G10",
522 
],
[
 "G11",
169 
],
[
 "G12",
523 
],
[
 "G13",
520 
],
[
 "G14",
176 
],
[
 "G15",
143 
],
[
 "G16",
107 
],
[
 "G17",
189 
],
[
 "G18",
472 
],
[
 "G19",
233 
],
[
 "G20",
335 
],
[
 "G21",
185 
],
[
 "G22",
238 
],
[
 "G23",
224 
],
[
 "G24",
304 
],
[
 "G25",
585 
],
[
 "G26",
184 
],
[
 "G27",
106 
],
[
 "G28",
372 
],
[
 "K01",
167 
],
[
 "K02",
185 
],
[
 "K03",
40 
],
[
 "K04",
247 
],
[
 "K06",
389 
],
[
 "K07",
216 
],
[
 "K08",
84 
],
[
 "K10",
103 
],
[
 "K11",
54 
],
[
 "K12",
49 
],
[
 "K15",
158 
],
[
 "K16",
110 
],
[
 "K17",
86 
],
[
 "K18",
242 
],
[
 "T01",
296 
],
[
 "Z02",
178 
] 
];
data.addColumn('string','Train');
data.addColumn('number','Man');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartBarChartID16ff73015a3b() {
var data = gvisDataBarChartID16ff73015a3b();
var options = {};
options["allowHtml"] = true;
options["width"] =   1000;
options["height"] =    600;

    var chart = new google.visualization.BarChart(
    document.getElementById('BarChartID16ff73015a3b')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartBarChartID16ff73015a3b);
})();
function displayChartBarChartID16ff73015a3b() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartBarChartID16ff73015a3b"></script>
 
<!-- divChart -->
  
<div id="BarChartID16ff73015a3b" 
  style="width: 1000; height: 600;">
</div>

--- .class #id

## Order the Chart of Trains!

<!-- BarChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataBarChartID16ff3f29f60a () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "D06",
888 
],
[
 "D04",
693 
],
[
 "D02",
660 
],
[
 "G09",
600 
],
[
 "G25",
585 
],
[
 "D15",
573 
],
[
 "G12",
523 
],
[
 "G10",
522 
],
[
 "G13",
520 
],
[
 "G18",
472 
],
[
 "D17",
447 
],
[
 "D09",
414 
],
[
 "G06",
402 
],
[
 "K06",
389 
],
[
 "G04",
379 
],
[
 "D10",
374 
],
[
 "D08",
373 
],
[
 "G28",
372 
],
[
 "D03",
365 
],
[
 "G20",
335 
],
[
 "D14",
307 
],
[
 "G24",
304 
],
[
 "T01",
296 
],
[
 "G08",
291 
],
[
 "D13",
280 
],
[
 "D16",
280 
],
[
 "D12",
260 
],
[
 "G07",
251 
] 
];
data.addColumn('string','Train');
data.addColumn('number','Man');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartBarChartID16ff3f29f60a() {
var data = gvisDataBarChartID16ff3f29f60a();
var options = {};
options["allowHtml"] = true;
options["width"] =   1000;
options["height"] =    600;

    var chart = new google.visualization.BarChart(
    document.getElementById('BarChartID16ff3f29f60a')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartBarChartID16ff3f29f60a);
})();
function displayChartBarChartID16ff3f29f60a() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartBarChartID16ff3f29f60a"></script>
 
<!-- divChart -->
  
<div id="BarChartID16ff3f29f60a" 
  style="width: 1000; height: 600;">
</div>

--- .class #id

## Time! -Annotated Time Line!

<!-- AnnotatedTimeLine generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataAnnotatedTimeLineID16ff4ce9d968 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 new Date(2015,0,8,0,57,0),
163,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,5,0),
null,
15,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,12,0),
27,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,52,0),
60,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,3,22,0),
null,
3,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,3,36,0),
62,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,27,0),
null,
null,
10,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,28,0),
null,
null,
null,
17,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,39,0),
45,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,44,0),
null,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,2,0),
null,
null,
26,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,23,0),
null,
null,
null,
null,
25,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,46,0),
null,
null,
37,
null,
13,
103,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,47,0),
null,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,3,0),
null,
null,
null,
null,
null,
null,
31,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,20,0),
53,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,28,0),
null,
31,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,30,0),
35,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,32,0),
null,
null,
null,
null,
null,
null,
null,
46,
null,
null,
null 
],
[
 new Date(2015,0,8,6,43,0),
50,
null,
null,
null,
null,
62,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,44,0),
null,
null,
78,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,57,0),
null,
null,
null,
30,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,1,0),
null,
20,
186,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,10,0),
363,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,24,0),
null,
null,
null,
45,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,30,0),
null,
null,
null,
null,
null,
null,
null,
121,
null,
null,
null 
],
[
 new Date(2015,0,8,7,39,0),
null,
48,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,43,0),
null,
null,
72,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,53,0),
null,
127,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,59,0),
null,
null,
71,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,4,0),
null,
null,
16,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,11,0),
null,
48,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,17,0),
504,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,22,0),
null,
null,
null,
26,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,30,0),
null,
null,
170,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,37,0),
null,
null,
null,
46,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,39,0),
null,
66,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,52,0),
null,
null,
9,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,57,0),
null,
null,
23,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,2,0),
null,
162,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,9,0),
null,
null,
93,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,10,0),
null,
null,
null,
null,
null,
137,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,32,0),
null,
null,
null,
null,
null,
null,
null,
null,
27,
null,
null 
],
[
 new Date(2015,0,8,9,39,0),
285,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,49,0),
180,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,50,0),
null,
null,
null,
null,
null,
null,
null,
59,
null,
null,
null 
],
[
 new Date(2015,0,8,9,56,0),
null,
null,
null,
null,
null,
null,
null,
12,
null,
null,
null 
],
[
 new Date(2015,0,8,9,57,0),
527,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,6,0),
null,
null,
null,
null,
111,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,9,0),
null,
null,
null,
null,
null,
304,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,13,0),
null,
null,
null,
null,
25,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,22,0),
null,
117,
null,
null,
null,
null,
null,
null,
null,
90,
null 
],
[
 new Date(2015,0,8,10,24,0),
null,
null,
36,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,34,0),
null,
44,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,46,0),
null,
56,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,55,0),
366,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,5,0),
null,
null,
null,
null,
67,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,6,0),
null,
null,
null,
57,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,11,0),
null,
36,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,15,0),
168,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,21,0),
null,
null,
110,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,24,0),
null,
null,
158,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,28,0),
175,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,35,0),
209,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,36,0),
null,
null,
null,
null,
195,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,39,0),
null,
80,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,51,0),
null,
29,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,56,0),
null,
null,
null,
null,
65,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,59,0),
null,
null,
null,
26,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,11,0),
null,
61,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,18,0),
null,
42,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,19,0),
422,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,21,0),
null,
null,
null,
null,
null,
177,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,32,0),
null,
19,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,41,0),
218,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,45,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
54,
null 
],
[
 new Date(2015,0,8,12,48,0),
null,
21,
68,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,52,0),
null,
67,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,59,0),
164,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,3,0),
null,
96,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,7,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
65,
null 
],
[
 new Date(2015,0,8,13,9,0),
null,
null,
38,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,14,0),
null,
24,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,16,0),
319,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,22,0),
223,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,27,0),
null,
null,
null,
40,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,31,0),
null,
null,
64,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,32,0),
null,
78,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,37,0),
null,
null,
null,
null,
null,
359,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,40,0),
null,
null,
67,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,43,0),
null,
37,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,54,0),
null,
null,
null,
null,
null,
null,
196,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,0,0),
null,
54,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,1,0),
null,
null,
18,
82,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,3,0),
null,
null,
null,
90,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,4,0),
362,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,6,0),
null,
53,
null,
null,
null,
null,
null,
null,
18,
null,
null 
],
[
 new Date(2015,0,8,14,8,0),
null,
null,
92,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,44,0),
null,
null,
59,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,45,0),
438,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,47,0),
null,
138,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,51,0),
null,
null,
216,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,52,0),
255,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,58,0),
137,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,6,0),
null,
null,
99,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,16,0),
null,
null,
null,
null,
null,
null,
null,
null,
24,
null,
null 
],
[
 new Date(2015,0,8,15,24,0),
268,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,26,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
35 
],
[
 new Date(2015,0,8,15,29,0),
null,
84,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,30,0),
null,
null,
76,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,31,0),
195,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,35,0),
null,
71,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,37,0),
212,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,41,0),
null,
32,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,47,0),
168,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,8,0),
null,
93,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,12,0),
null,
null,
48,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,15,0),
null,
27,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,21,0),
null,
33,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,30,0),
344,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,31,0),
null,
40,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,42,0),
null,
null,
null,
127,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,44,0),
null,
null,
162,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,47,0),
149,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,52,0),
null,
null,
null,
27,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,53,0),
null,
null,
38,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,54,0),
145,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,5,0),
145,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,12,0),
223,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,13,0),
null,
71,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,30,0),
null,
29,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,42,0),
null,
17,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,43,0),
163,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,49,0),
null,
17,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,50,0),
null,
null,
null,
55,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,51,0),
null,
null,
105,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,59,0),
null,
33,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,0,0),
195,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,8,0),
null,
null,
null,
14,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,19,0),
121,
null,
22,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,25,0),
172,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,26,0),
null,
51,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,28,0),
null,
null,
null,
null,
null,
null,
null,
16,
null,
null,
null 
],
[
 new Date(2015,0,8,18,37,0),
null,
null,
35,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,43,0),
null,
31,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,45,0),
null,
null,
null,
null,
null,
325,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,49,0),
87,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,52,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
27,
null 
],
[
 new Date(2015,0,8,18,59,0),
93,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,3,0),
null,
null,
24,
22,
null,
null,
57,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,6,0),
194,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,16,0),
null,
17,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,31,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
57,
null 
],
[
 new Date(2015,0,8,19,33,0),
null,
15,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,36,0),
173,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,43,0),
null,
13,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,51,0),
127,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,54,0),
null,
null,
17,
5,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,55,0),
null,
29,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,56,0),
null,
null,
null,
null,
null,
163,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,1,0),
null,
null,
29,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,6,0),
71,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,14,0),
null,
null,
null,
null,
null,
null,
27,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,19,0),
null,
16,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,21,0),
166,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,24,0),
null,
null,
null,
14,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,35,0),
null,
11,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,47,0),
null,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,51,0),
null,
10,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,4,0),
null,
16,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,11,0),
null,
null,
null,
4,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,12,0),
null,
null,
21,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,13,0),
null,
null,
22,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,24,0),
null,
null,
null,
3,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,42,0),
null,
null,
null,
null,
null,
null,
null,
13,
null,
null,
null 
] 
];
data.addColumn('datetime','Time');
data.addColumn('number','ZD111-01');
data.addColumn('number','ZD326');
data.addColumn('number','ZD250');
data.addColumn('number','ZD192');
data.addColumn('number','ZD111-02');
data.addColumn('number','ZD190-01');
data.addColumn('number','ZD190-02');
data.addColumn('number','ZD062');
data.addColumn('number','ZD022');
data.addColumn('number','ZD311');
data.addColumn('number','ZD120');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartAnnotatedTimeLineID16ff4ce9d968() {
var data = gvisDataAnnotatedTimeLineID16ff4ce9d968();
var options = {};
options["width"] =   1000;
options["height"] =    400;

    var chart = new google.visualization.AnnotatedTimeLine(
    document.getElementById('AnnotatedTimeLineID16ff4ce9d968')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "annotatedtimeline";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartAnnotatedTimeLineID16ff4ce9d968);
})();
function displayChartAnnotatedTimeLineID16ff4ce9d968() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartAnnotatedTimeLineID16ff4ce9d968"></script>
 
<!-- divChart -->
  
<div id="AnnotatedTimeLineID16ff4ce9d968" 
  style="width: 1000; height: 400;">
</div>

--- .class #id

## Time! -Annotated Time Chart

<!-- AnnotationChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataAnnotationChartID16ff2a753077 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 new Date(2015,0,8,0,57,0),
163,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,5,0),
null,
15,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,12,0),
27,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,52,0),
60,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,3,22,0),
null,
3,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,3,36,0),
62,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,27,0),
null,
null,
10,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,28,0),
null,
null,
null,
17,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,39,0),
45,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,44,0),
null,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,2,0),
null,
null,
26,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,23,0),
null,
null,
null,
null,
25,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,46,0),
null,
null,
37,
null,
13,
103,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,47,0),
null,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,3,0),
null,
null,
null,
null,
null,
null,
31,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,20,0),
53,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,28,0),
null,
31,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,30,0),
35,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,32,0),
null,
null,
null,
null,
null,
null,
null,
46,
null,
null,
null 
],
[
 new Date(2015,0,8,6,43,0),
50,
null,
null,
null,
null,
62,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,44,0),
null,
null,
78,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,57,0),
null,
null,
null,
30,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,1,0),
null,
20,
186,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,10,0),
363,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,24,0),
null,
null,
null,
45,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,30,0),
null,
null,
null,
null,
null,
null,
null,
121,
null,
null,
null 
],
[
 new Date(2015,0,8,7,39,0),
null,
48,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,43,0),
null,
null,
72,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,53,0),
null,
127,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,59,0),
null,
null,
71,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,4,0),
null,
null,
16,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,11,0),
null,
48,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,17,0),
504,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,22,0),
null,
null,
null,
26,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,30,0),
null,
null,
170,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,37,0),
null,
null,
null,
46,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,39,0),
null,
66,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,52,0),
null,
null,
9,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,57,0),
null,
null,
23,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,2,0),
null,
162,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,9,0),
null,
null,
93,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,10,0),
null,
null,
null,
null,
null,
137,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,32,0),
null,
null,
null,
null,
null,
null,
null,
null,
27,
null,
null 
],
[
 new Date(2015,0,8,9,39,0),
285,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,49,0),
180,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,50,0),
null,
null,
null,
null,
null,
null,
null,
59,
null,
null,
null 
],
[
 new Date(2015,0,8,9,56,0),
null,
null,
null,
null,
null,
null,
null,
12,
null,
null,
null 
],
[
 new Date(2015,0,8,9,57,0),
527,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,6,0),
null,
null,
null,
null,
111,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,9,0),
null,
null,
null,
null,
null,
304,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,13,0),
null,
null,
null,
null,
25,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,22,0),
null,
117,
null,
null,
null,
null,
null,
null,
null,
90,
null 
],
[
 new Date(2015,0,8,10,24,0),
null,
null,
36,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,34,0),
null,
44,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,46,0),
null,
56,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,55,0),
366,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,5,0),
null,
null,
null,
null,
67,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,6,0),
null,
null,
null,
57,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,11,0),
null,
36,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,15,0),
168,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,21,0),
null,
null,
110,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,24,0),
null,
null,
158,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,28,0),
175,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,35,0),
209,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,36,0),
null,
null,
null,
null,
195,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,39,0),
null,
80,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,51,0),
null,
29,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,56,0),
null,
null,
null,
null,
65,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,59,0),
null,
null,
null,
26,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,11,0),
null,
61,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,18,0),
null,
42,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,19,0),
422,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,21,0),
null,
null,
null,
null,
null,
177,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,32,0),
null,
19,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,41,0),
218,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,45,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
54,
null 
],
[
 new Date(2015,0,8,12,48,0),
null,
21,
68,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,52,0),
null,
67,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,59,0),
164,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,3,0),
null,
96,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,7,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
65,
null 
],
[
 new Date(2015,0,8,13,9,0),
null,
null,
38,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,14,0),
null,
24,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,16,0),
319,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,22,0),
223,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,27,0),
null,
null,
null,
40,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,31,0),
null,
null,
64,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,32,0),
null,
78,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,37,0),
null,
null,
null,
null,
null,
359,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,40,0),
null,
null,
67,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,43,0),
null,
37,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,54,0),
null,
null,
null,
null,
null,
null,
196,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,0,0),
null,
54,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,1,0),
null,
null,
18,
82,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,3,0),
null,
null,
null,
90,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,4,0),
362,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,6,0),
null,
53,
null,
null,
null,
null,
null,
null,
18,
null,
null 
],
[
 new Date(2015,0,8,14,8,0),
null,
null,
92,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,44,0),
null,
null,
59,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,45,0),
438,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,47,0),
null,
138,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,51,0),
null,
null,
216,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,52,0),
255,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,58,0),
137,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,6,0),
null,
null,
99,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,16,0),
null,
null,
null,
null,
null,
null,
null,
null,
24,
null,
null 
],
[
 new Date(2015,0,8,15,24,0),
268,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,26,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
35 
],
[
 new Date(2015,0,8,15,29,0),
null,
84,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,30,0),
null,
null,
76,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,31,0),
195,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,35,0),
null,
71,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,37,0),
212,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,41,0),
null,
32,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,47,0),
168,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,8,0),
null,
93,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,12,0),
null,
null,
48,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,15,0),
null,
27,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,21,0),
null,
33,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,30,0),
344,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,31,0),
null,
40,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,42,0),
null,
null,
null,
127,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,44,0),
null,
null,
162,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,47,0),
149,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,52,0),
null,
null,
null,
27,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,53,0),
null,
null,
38,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,54,0),
145,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,5,0),
145,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,12,0),
223,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,13,0),
null,
71,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,30,0),
null,
29,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,42,0),
null,
17,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,43,0),
163,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,49,0),
null,
17,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,50,0),
null,
null,
null,
55,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,51,0),
null,
null,
105,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,59,0),
null,
33,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,0,0),
195,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,8,0),
null,
null,
null,
14,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,19,0),
121,
null,
22,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,25,0),
172,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,26,0),
null,
51,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,28,0),
null,
null,
null,
null,
null,
null,
null,
16,
null,
null,
null 
],
[
 new Date(2015,0,8,18,37,0),
null,
null,
35,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,43,0),
null,
31,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,45,0),
null,
null,
null,
null,
null,
325,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,49,0),
87,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,52,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
27,
null 
],
[
 new Date(2015,0,8,18,59,0),
93,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,3,0),
null,
null,
24,
22,
null,
null,
57,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,6,0),
194,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,16,0),
null,
17,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,31,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
57,
null 
],
[
 new Date(2015,0,8,19,33,0),
null,
15,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,36,0),
173,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,43,0),
null,
13,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,51,0),
127,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,54,0),
null,
null,
17,
5,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,55,0),
null,
29,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,56,0),
null,
null,
null,
null,
null,
163,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,1,0),
null,
null,
29,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,6,0),
71,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,14,0),
null,
null,
null,
null,
null,
null,
27,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,19,0),
null,
16,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,21,0),
166,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,24,0),
null,
null,
null,
14,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,35,0),
null,
11,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,47,0),
null,
22,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,20,51,0),
null,
10,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,4,0),
null,
16,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,11,0),
null,
null,
null,
4,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,12,0),
null,
null,
21,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,13,0),
null,
null,
22,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,24,0),
null,
null,
null,
3,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,21,42,0),
null,
null,
null,
null,
null,
null,
null,
13,
null,
null,
null 
] 
];
data.addColumn('datetime','Time');
data.addColumn('number','ZD111-01');
data.addColumn('number','ZD326');
data.addColumn('number','ZD250');
data.addColumn('number','ZD192');
data.addColumn('number','ZD111-02');
data.addColumn('number','ZD190-01');
data.addColumn('number','ZD190-02');
data.addColumn('number','ZD062');
data.addColumn('number','ZD022');
data.addColumn('number','ZD311');
data.addColumn('number','ZD120');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartAnnotationChartID16ff2a753077() {
var data = gvisDataAnnotationChartID16ff2a753077();
var options = {};
options["width"] =   1000;
options["height"] =    400;
options["displayExactValues"] = false;

    var chart = new google.visualization.AnnotationChart(
    document.getElementById('AnnotationChartID16ff2a753077')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "annotationchart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartAnnotationChartID16ff2a753077);
})();
function displayChartAnnotationChartID16ff2a753077() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartAnnotationChartID16ff2a753077"></script>
 
<!-- divChart -->
  
<div id="AnnotationChartID16ff2a753077" 
  style="width: 1000; height: 400;">
</div>

--- .class #id

## Look! -Visitor Flow Based On Station

<!-- AnnotationChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataAnnotationChartID16ff7e5d4b8f () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 new Date(2015,0,8,0,0,0),
163,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,0,0),
87,
15,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,3,0,0),
62,
3,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,0,0),
45,
22,
17,
10,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,0,0),
null,
22,
null,
63,
38,
103,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,0,0),
138,
31,
30,
78,
null,
62,
46,
31,
null,
null,
null 
],
[
 new Date(2015,0,8,7,0,0),
363,
195,
45,
329,
null,
null,
121,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,0,0),
504,
114,
72,
218,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,0,0),
992,
162,
null,
93,
null,
137,
71,
null,
27,
null,
null 
],
[
 new Date(2015,0,8,10,0,0),
366,
217,
null,
36,
136,
304,
null,
null,
null,
90,
null 
],
[
 new Date(2015,0,8,11,0,0),
552,
145,
83,
268,
327,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,0,0),
804,
210,
null,
68,
null,
177,
null,
null,
null,
54,
null 
],
[
 new Date(2015,0,8,13,0,0),
542,
235,
40,
169,
null,
359,
null,
196,
null,
65,
null 
],
[
 new Date(2015,0,8,14,0,0),
1192,
245,
172,
385,
null,
null,
null,
null,
18,
null,
null 
],
[
 new Date(2015,0,8,15,0,0),
843,
187,
null,
175,
null,
null,
null,
null,
24,
null,
35 
],
[
 new Date(2015,0,8,16,0,0),
638,
193,
154,
248,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,0,0),
531,
167,
55,
105,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,0,0),
668,
82,
14,
57,
null,
325,
16,
null,
null,
27,
null 
],
[
 new Date(2015,0,8,19,0,0),
494,
96,
27,
41,
null,
163,
null,
57,
null,
57,
null 
],
[
 new Date(2015,0,8,20,0,0),
237,
59,
14,
29,
null,
null,
null,
27,
null,
null,
null 
],
[
 new Date(2015,0,8,21,0,0),
null,
16,
7,
43,
null,
null,
13,
null,
null,
null,
null 
] 
];
data.addColumn('datetime','Time');
data.addColumn('number','ZD111-01');
data.addColumn('number','ZD326');
data.addColumn('number','ZD192');
data.addColumn('number','ZD250');
data.addColumn('number','ZD111-02');
data.addColumn('number','ZD190-01');
data.addColumn('number','ZD062');
data.addColumn('number','ZD190-02');
data.addColumn('number','ZD022');
data.addColumn('number','ZD311');
data.addColumn('number','ZD120');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartAnnotationChartID16ff7e5d4b8f() {
var data = gvisDataAnnotationChartID16ff7e5d4b8f();
var options = {};
options["width"] =   1000;
options["height"] =    400;
options["displayExactValues"] = true;

    var chart = new google.visualization.AnnotationChart(
    document.getElementById('AnnotationChartID16ff7e5d4b8f')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "annotationchart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartAnnotationChartID16ff7e5d4b8f);
})();
function displayChartAnnotationChartID16ff7e5d4b8f() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartAnnotationChartID16ff7e5d4b8f"></script>
 
<!-- divChart -->
  
<div id="AnnotationChartID16ff7e5d4b8f" 
  style="width: 1000; height: 400;">
</div>

--- .class #id 

## Visitor Flow Based On Train

<!-- AnnotationChart generated in R 3.2.4 by googleVis 0.5.10 package -->
<!-- Sun Jun 12 18:19:59 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataAnnotationChartID16ff431baf3b () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 new Date(2015,0,8,0,0,0),
163,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,2,0,0),
15,
27,
60,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,3,0,0),
null,
3,
null,
62,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,4,0,0),
null,
10,
17,
22,
45,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,5,0,0),
null,
null,
26,
37,
22,
103,
13,
25,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,6,0,0),
null,
null,
null,
46,
78,
31,
null,
61,
62,
53,
35,
50,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,7,0,0),
null,
null,
null,
null,
71,
231,
20,
72,
121,
22,
26,
null,
490,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,8,0,0),
null,
null,
null,
null,
null,
null,
16,
null,
66,
9,
49,
94,
170,
504,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,9,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
152,
null,
189,
527,
149,
285,
180,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,10,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
146,
36,
117,
44,
304,
366,
111,
25,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,11,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
215,
null,
null,
null,
110,
106,
36,
29,
209,
175,
168,
195,
67,
65,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,12,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
42,
129,
21,
67,
19,
54,
177,
218,
164,
422,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,13,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
38,
null,
null,
null,
40,
null,
null,
24,
64,
143,
37,
163,
319,
133,
422,
223,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,14,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
18,
92,
null,
null,
null,
18,
90,
null,
54,
147,
151,
112,
255,
500,
438,
137,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,15,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
35,
null,
99,
null,
null,
null,
null,
null,
null,
null,
null,
71,
100,
84,
32,
195,
168,
268,
212,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,16,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
48,
null,
null,
null,
65,
67,
255,
160,
149,
344,
145,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,17,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
84,
176,
17,
256,
162,
163,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,18,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
22,
51,
14,
51,
325,
226,
121,
87,
199,
93,
null,
null,
null,
null,
null,
null 
],
[
 new Date(2015,0,8,19,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
24,
57,
22,
22,
20,
34,
13,
280,
127,
163,
173,
null,
null 
],
[
 new Date(2015,0,8,20,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
65,
null,
null,
null,
null,
null,
null,
11,
27,
16,
81,
166 
],
[
 new Date(2015,0,8,21,0,0),
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
null,
35,
21,
null,
4,
19 
] 
];
data.addColumn('datetime','Time');
data.addColumn('number','Z02');
data.addColumn('number','K03');
data.addColumn('number','K10');
data.addColumn('number','K01');
data.addColumn('number','K07');
data.addColumn('number','D03');
data.addColumn('number','K12');
data.addColumn('number','K15');
data.addColumn('number','D05');
data.addColumn('number','K08');
data.addColumn('number','K16');
data.addColumn('number','T01');
data.addColumn('number','D02');
data.addColumn('number','D04');
data.addColumn('number','D06');
data.addColumn('number','D07');
data.addColumn('number','G06');
data.addColumn('number','G23');
data.addColumn('number','D09');
data.addColumn('number','G18');
data.addColumn('number','K02');
data.addColumn('number','K11');
data.addColumn('number','G07');
data.addColumn('number','G24');
data.addColumn('number','K04');
data.addColumn('number','K06');
data.addColumn('number','K17');
data.addColumn('number','K18');
data.addColumn('number','D11');
data.addColumn('number','G04');
data.addColumn('number','G08');
data.addColumn('number','G25');
data.addColumn('number','D08');
data.addColumn('number','D13');
data.addColumn('number','D15');
data.addColumn('number','G20');
data.addColumn('number','D10');
data.addColumn('number','G09');
data.addColumn('number','G10');
data.addColumn('number','G11');
data.addColumn('number','D12');
data.addColumn('number','G05');
data.addColumn('number','G12');
data.addColumn('number','G28');
data.addColumn('number','G01');
data.addColumn('number','G13');
data.addColumn('number','G26');
data.addColumn('number','D14');
data.addColumn('number','G14');
data.addColumn('number','G22');
data.addColumn('number','D17');
data.addColumn('number','G03');
data.addColumn('number','G15');
data.addColumn('number','G16');
data.addColumn('number','G19');
data.addColumn('number','G27');
data.addColumn('number','D16');
data.addColumn('number','D18');
data.addColumn('number','D19');
data.addColumn('number','G17');
data.addColumn('number','G02');
data.addColumn('number','G21');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartAnnotationChartID16ff431baf3b() {
var data = gvisDataAnnotationChartID16ff431baf3b();
var options = {};
options["width"] =   1000;
options["height"] =    400;
options["displayExactValues"] = true;

    var chart = new google.visualization.AnnotationChart(
    document.getElementById('AnnotationChartID16ff431baf3b')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "annotationchart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartAnnotationChartID16ff431baf3b);
})();
function displayChartAnnotationChartID16ff431baf3b() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartAnnotationChartID16ff431baf3b"></script>
 
<!-- divChart -->
  
<div id="AnnotationChartID16ff431baf3b" 
  style="width: 1000; height: 400;">
</div>
