---
title       : LOOPdata
subtitle    : Commercial Nuclear Power Experiences
author      : Farkas
job         : praEngineer
logo        : logo_small.jpg
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

1. Risk exposure
2. NRC event data
3. EIA event data

--- .class #id 

## Exposure

<h4>Total hours of exposure in one year at all 72 sites </h4>

```
## [1] 630720
```

--- .class #id 

## NRC Event Logs

Plant operators keep the NRC informed on a defined set of problems via phone calls log as <a href="http://www.nrc.gov/reading-rm/doc-collections/event-status/event/">events</a>.

More complex events are described via <a href="https://lersearch.inl.gov/LERSearchCriteria.aspx">reports</a>.  Some of these describe "loss of offsite power"" events.

--- .class #id 

## EIA Appendix B Logs 

<h3>Form OE-417 logs</h3>

<a href="http://www.eia.gov/electricity/monthly/">Major Disturbances and Unusual Occurrences</a>, particularly Table B.1

<!-- html table generated in R 3.1.0 by xtable 1.7-3 package -->
<!-- Sun Jun 22 21:42:22 2014 -->
<TABLE border=1>
<TR> <TH>  </TH> <TH> Event.Date.and.Time </TH> <TH> Utility.Power.Pool </TH> <TH> NERC.Region </TH> <TH> Type.of.Disturbance </TH>  </TR>
  <TR> <TD align="right"> 1 </TD> <TD> 01/06/2014  7:01 AM </TD> <TD> ERCOT </TD> <TD> TRE </TD> <TD> Public Appeal due to Severe Weather - Cold </TD> </TR>
  <TR> <TD align="right"> 2 </TD> <TD> 01/06/2014  7:01 AM </TD> <TD> ERCOT </TD> <TD> TRE </TD> <TD> Public Appeal due to Severe Weather - Cold </TD> </TR>
  <TR> <TD align="right"> 3 </TD> <TD> 01/06/2014  7:50 PM </TD> <TD> PJM Interconnection </TD> <TD> RFC </TD> <TD> Voltage Reduction due to Severe Weather - Cold </TD> </TR>
  <TR> <TD align="right"> 4 </TD> <TD> 01/06/2014  7:50 PM </TD> <TD> PJM Interconnection </TD> <TD> RFC </TD> <TD> Voltage Reduction due to Severe Weather - Cold </TD> </TR>
  <TR> <TD align="right"> 5 </TD> <TD> 01/06/2014  7:50 PM </TD> <TD> PPL Electric Utilities Corp </TD> <TD> RFC </TD> <TD> Voltage Reduction due to Severe Weather - Cold </TD> </TR>
  <TR> <TD align="right"> 6 </TD> <TD> 01/06/2014  7:50 PM </TD> <TD> Potomac Electric Power Co </TD> <TD> RFC </TD> <TD> Voltage Reduction due to Severe Weather - Cold </TD> </TR>
   </TABLE>

--- .class #id 

## Anticipating LOOP

A statistical method shows how the likelihood of a grid-induced LOOP is a strong function of the location of the plant (i.e., regional dependence) as well as the season of the year (i.e., seasonal dependence).  To establish a statistically meaningful data set, grid-centered LOOP events were enriched by merging traditional LOOP events (NRC) with events hypothesized to be pre-cursors to LOOP events (EIA).  The duration of grid-centered LOOPs (directly related to the LOOP-non-recovery probability) averaged from three to nine hours.  The effect on the non-recovery probability as a result of this unexpectedly long duration is left to a future report.

