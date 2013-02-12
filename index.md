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
<!-- Tue Feb 12 15:11:25 2013 -->
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
<!-- Tue Feb 12 15:11:26 2013 -->


<!-- jsHeader -->
<script type="text/javascript" src="http://www.google.com/jsapi">
</script>
<script type="text/javascript">
 
// jsData 
function gvisDataMotionChartID20914bd7b078 ()
{
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Italy",
new Date(2013,1,12),
"uploadedDate",
"2012",
27,
"Marine" 
],
[
 "Austria",
new Date(2013,1,12),
"uploadedDate",
"2011",
7,
"Terrestrial" 
] 
];
data.addColumn('string','action');
data.addColumn('date','submissionDate');
data.addColumn('string','year');
data.addColumn('string','parameterNum');
data.addColumn('number','countryName');
data.addColumn('string','domainName');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMotionChartID20914bd7b078() {
  var data = gvisDataMotionChartID20914bd7b078();
  var options = {};
options["width"] =    600;
options["height"] =    500;

     var chart = new google.visualization.MotionChart(
       document.getElementById('MotionChartID20914bd7b078')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart 
function displayChartMotionChartID20914bd7b078()
{
  google.load("visualization", "1", { packages:["motionchart"] }); 
  google.setOnLoadCallback(drawChartMotionChartID20914bd7b078);
}
 
// jsChart 
displayChartMotionChartID20914bd7b078()
 
<!-- jsFooter -->  
//-->
</script>
 
<!-- divChart -->
  
<div id="MotionChartID20914bd7b078"
  style="width: 600px; height: 500px;">
</div>







