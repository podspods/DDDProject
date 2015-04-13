Trees In Paris
========================================================
author: Emile
date: date


First Slide
========================================================
Sommaire<br>
For more details on authoring R presentations click the
**Help** button on the toolbar.

- Bullet 1
- Bullet 2
- Bullet 3

Slide With Code
========================================================
Paris have 90 000 trees
Paris have 2 265 886  inhabitants 

a personn consum  700g a day of oxygen
average breathing = 20l/min .  so 28 800  l/day
air conten 20% oxygen  so 5 760l of oxygen a days



Slide With Code
========================================================
```
cd /myDirectory
```
go to the directory to git

```
git init 
```
init an empty  repository 

```
git add *

```
Add files in the repository  (* for all )

```
git commit -a -m "Initial Comment "
```
Commit for the first time 

```
git remote add origin https://github.com/podspods/DDDProject.git
```
prepare pour pushing 

```
git push -u origin master
```
push in github



Slide githup for web site
========================================================

```
git branch gh-pages
```
create a branche for the web site

```
git checkout gh-pages
```
switch to the branche gh-pages

```
touch .nojekyll
```
create .nojekyll file because html 


Slide With Code
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](TreesInParis-figure/unnamed-chunk-2-1.png) 
