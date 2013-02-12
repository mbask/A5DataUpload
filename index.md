---
title       : Data uploading and Metadata editing
subtitle    : (15 Feb - 08 Mar 2013) - Summary stats
author      : Marco Bascietto, Giorgio Matteucci
job         : EnvEurope A5 "Testing in the Field"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---












## State of uploading process

* Last updated ``2013-02-12``
* Deadline for data submission: `2013-03-08`
* Days to deadline: ``24``
* Total number of sites sampled in 2012: ``59``; stations: ``61``


<!-- html table generated in R 2.15.2 by xtable 1.7-0 package -->
<!-- Tue Feb 12 15:19:22 2013 -->
<TABLE border=1>
<TR> <TH>  </TH> <TH> No. uploaded </TH> <TH> No. metadated </TH> <TH> Total no. </TH> <TH> Upload ratio </TH> <TH> Metadata ratio </TH>  </TR>
  <TR> <TD align="right"> Year2012 </TD> <TD align="right">  27 </TD> <TD align="right">   0 </TD> <TD align="right"> 1950 </TD> <TD align="right"> 0.01 </TD> <TD align="right"> 0.00 </TD> </TR>
  <TR> <TD align="right"> Year2011 </TD> <TD align="right">   7 </TD> <TD align="right">   0 </TD> <TD align="right"> 218 </TD> <TD align="right"> 0.03 </TD> <TD align="right"> 0.00 </TD> </TR>
  <TR> <TD align="right"> Sum </TD> <TD align="right">  34 </TD> <TD align="right">   0 </TD> <TD align="right"> 2168 </TD> <TD align="right"> 0.02 </TD> <TD align="right"> 0.00 </TD> </TR>
   </TABLE>





---

## Aggregated data by domain

![plot of chunk aggrDataByDomain](figure/A5DAMU-1aggrDataByDomain.png) 


---

## Aggregated data by country

![plot of chunk aggrDatabyCountry](figure/A5DAMU-1aggrDatabyCountry.png) 



---

## Motion chart

<!-- MotionChart generated in R 2.15.2 by googleVis 0.3.3 package -->
<!-- Tue Feb 12 15:19:23 2013 -->


<!-- jsHeader -->
<script type="text/javascript" src="http://www.google.com/jsapi">
</script>
<script type="text/javascript">
 
// jsData 
function gvisDataMotionChartID209178463972 ()
{
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "SI000049",
new Date(2013,1,12),
2011,
7,
"Austria",
"uploadedDate",
"Terrestrial" 
],
[
 "SI001246",
new Date(2013,1,12),
2012,
27,
"Italy",
"uploadedDate",
"Marine" 
] 
];
data.addColumn('string','siteLTERCode');
data.addColumn('date','submissionDate');
data.addColumn('number','year');
data.addColumn('number','parameterNum');
data.addColumn('string','countryName');
data.addColumn('string','action');
data.addColumn('string','domainName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMotionChartID209178463972() {
  var data = gvisDataMotionChartID209178463972();
  var options = {};
options["width"] =    600;
options["height"] =    500;

     var chart = new google.visualization.MotionChart(
       document.getElementById('MotionChartID209178463972')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart 
function displayChartMotionChartID209178463972()
{
  google.load("visualization", "1", { packages:["motionchart"] }); 
  google.setOnLoadCallback(drawChartMotionChartID209178463972);
}
 
// jsChart 
displayChartMotionChartID209178463972()
 
<!-- jsFooter -->  
//-->
</script>
 
<!-- divChart -->
  
<div id="MotionChartID209178463972"
  style="width: 600px; height: 500px;">
</div>







