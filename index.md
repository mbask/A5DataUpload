---
title       : Data uploading and Metadata editing
subtitle    : 15 Feb - 08 Mar 2013 - Summary stats
author      : Marco Bascietto, Giorgio Matteucci
job         : EnvEurope A5 "Testing in the Field" - Use arrows to move between slides
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user: mbask
  repo: A5DataUpload
---












## State of uploading process

* Last updated ``2013-02-21``
* Deadline for data submission: `2013-03-08`
* Days to deadline: ``15``
* Total number of sites sampled in 2012: ``60``; stations: ``63``


<!-- html table generated in R 2.15.2 by xtable 1.7-0 package -->
<!-- Thu Feb 21 18:18:12 2013 -->
<TABLE border=1>
<TR> <TH>  </TH> <TH> No. uploaded </TH> <TH> No. metadated </TH> <TH> Total no. </TH> <TH> Upload ratio </TH> <TH> Metadata ratio </TH>  </TR>
  <TR> <TD align="right"> Year2012 </TD> <TD align="right">  18 </TD> <TD align="right">   0 </TD> <TD align="right"> 1972 </TD> <TD align="right"> 0.01 </TD> <TD align="right"> 0.00 </TD> </TR>
  <TR> <TD align="right"> Year2011 </TD> <TD align="right">   0 </TD> <TD align="right">   0 </TD> <TD align="right"> 242 </TD> <TD align="right"> 0.00 </TD> <TD align="right"> 0.00 </TD> </TR>
  <TR> <TD align="right"> Sum </TD> <TD align="right">  18 </TD> <TD align="right">   0 </TD> <TD align="right"> 2214 </TD> <TD align="right"> 0.01 </TD> <TD align="right"> 0.00 </TD> </TR>
   </TABLE>





---

## Aggregated data

![plot of chunk aggrDataByDomain](figure/A5DAMU-1aggrDataByDomain.png) 


---

## Submissions trend
 

<!-- MotionChart generated in R 2.15.2 by googleVis 0.3.3 package -->
<!-- Thu Feb 21 18:18:12 2013 -->


<!-- jsHeader -->
<script type="text/javascript" src="http://www.google.com/jsapi">
</script>
<script type="text/javascript">
 
// jsData 
function gvisDataMotionChartID358b1eb2ac8f ()
{
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "SI001231-Cedrino",
new Date(2013,1,21),
0.75,
9,
"Italy",
12,
"uploadedDate",
"Freshwater-lake" 
],
[
 "SI001231-Temo",
new Date(2013,1,21),
0.375,
9,
"Italy",
24,
"uploadedDate",
"Freshwater-lake" 
] 
];
data.addColumn('string','siteLTERCode');
data.addColumn('date','submissionDate');
data.addColumn('number','submissionRatio');
data.addColumn('number','parameterNum');
data.addColumn('string','countryName');
data.addColumn('number','totParameters');
data.addColumn('string','action');
data.addColumn('string','domainName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMotionChartID358b1eb2ac8f() {
  var data = gvisDataMotionChartID358b1eb2ac8f();
  var options = {};
options["width"] =    600;
options["height"] =    500;

     var chart = new google.visualization.MotionChart(
       document.getElementById('MotionChartID358b1eb2ac8f')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart 
function displayChartMotionChartID358b1eb2ac8f()
{
  google.load("visualization", "1", { packages:["motionchart"] }); 
  google.setOnLoadCallback(drawChartMotionChartID358b1eb2ac8f);
}
 
// jsChart 
displayChartMotionChartID358b1eb2ac8f()
 
<!-- jsFooter -->  
//-->
</script>
 
<!-- divChart -->
  
<div id="MotionChartID358b1eb2ac8f"
  style="width: 600px; height: 500px;">
</div>







