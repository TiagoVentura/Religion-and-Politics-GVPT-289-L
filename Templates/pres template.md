Title
========================================================
author: Author 
date: Author Affiliation
font-import: http://fonts.googleapis.com/css?family=Garamond
font-family: 'Garamond'
autosize: true</code>

DATE

<style>

/* Altering the Title Slides */
.reveal body {
  background: #EDE0CF;
}

/* slide titles */
.reveal h3 { 
  font-size: 60px;
  color: #666699;
}

/* subheader titles */
.reveal h2 { 
  font-size: 100px;
}

/* starter-section */
.starter-section .reveal .state-background {
  background: #A3A5AD;
} 
.starter-section .reveal h3 {
    font-size: 100px;
    color: white;
}

/* Special Slide Type */
.exclaim .reveal .state-background {
  background: #ff8080;
} 
.exclaim .reveal h3 {
  font-size: 150px;
  color: black;
}
.exclaim .reveal p {
  color: white;
}

</style>



Overview 
========================================================

Today, we will cover:


1. Brazilian Soccer Team  

2. Germany Soccer Team

3. Next World Cup

4. Are we likely to have a new 7x1?


All my slides will be available via:
.....

Brazilian Soccer Team 2014 x 2018
=======================================================

<div align="center">
<img src="brazil2014.png" width=350 height=200>
</div>

***
<div align="center">
<img src="brazil2018.png" width=350 height=200>
</div>



Discussion
==================================================
incremental:true 

<font size = "32px">

Is it clear the difference?

</font>



Germany Soccer Team
============================================================
incremental:true

<div align="center">
<img src="germany.png" width=600 height=500>
</div>

***

**Lahm**: _out_

**Klose**: _out_

**Schwainstaiger**: Thanks good retired!

Are we likely to have a new 7x1?
============================================================



```r
#In case you want to use some code to predict!

soccerpred <- function(x, y){
  mod<- lm(y~x) 
  summary(mod)
  
}

# I am sure some statiticians know how to model this. But, soccer is all about magic, not math
```

My opinion: I hope not!
===========================================================
type:exclaim



==========================================================
type:prompt

<center>
# See you all in Russia 2018

<center>



