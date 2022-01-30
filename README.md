# Analysis of soccer team formations
Based on the Kaggle European Soccer Database :
* 25k+ matches<img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Kaggle_logo.png" alt="alt text" width="200" height="whatever" align="right">
* players & teams attributes for European Professional Football
* link : ***https://www.kaggle.com/hugomathien/soccer***

&nbsp;&nbsp;


---

## Introduction

The goal of this notebook was to analyse some characteritics of the french teams during the Ligue 1 season 2015-2016. The study will be based on analysing the various postionning of players and the correlation between their position on the field and their characteristcs.

<a href="url"><img src="https://github.com/GitBrunoCode/Analysis-of-soccer-team-formations/blob/main/pictures/foot.png" align="left" width=50% height=50% ></a>
<a href="url"><img src="https://github.com/GitBrunoCode/Analysis-of-soccer-team-formations/blob/main/pictures/teamformation.PNG" align="right" width=40% height=40% ></a>

<a href="url"><img src="https://github.com/GitBrunoCode/Analysis-of-soccer-team-formations/blob/main/pictures/heatmap.png" align="left" width=50% height=50% ></a>

<a href="url"><img src="https://github.com/GitBrunoCode/Analysis-of-soccer-team-formations/blob/main/pictures/weight.png" align="right" width=40% height=40%></a>

&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  
&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  
&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  
&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  
&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  
&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  
&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  
&nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  &nbsp;   &nbsp;   &nbsp;   &nbsp;   &nbsp;  


---

## Table of Contents

1. [Installation](#Installation)
2. [Author Info](#author-info)

---

## Installation

### ***Download the files***
<a href="url"><img src="https://cdn-icons-png.flaticon.com/512/28/28792.png" align="right" width=10% height=10% ></a>
* database.rar
* unzip the file
* set the path into the jupyter notebook


&nbsp;&nbsp;

### ***Required Librairies***

* numpy
<a href="url"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/2560px-Pandas_logo.svg.png" align="right" width=20% height=20% ></a>
* pandas
* sqlite3
* matplotlib.pyplot
<a href="url"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/SQLite370.svg/2560px-SQLite370.svg.png" align="right" width=20% height=20% ></a>
* seaborn
* folium
* math
* collections 
<a href="url"><img src="https://jupyter.org/assets/share.png" align="right" width=20% height=20% ></a>
* scipy.stats 
* warnings


[Back To The Top](#Table-of-contents)

---

## Author Info

* Pincet Bruno 
    * [Github - @GitBrunoCode](https://github.com/GitBrunoCode)
    * [Linkedin - PINCET Bruno](https://www.linkedin.com/in/bruno-pincet/)


[Back To The Top](#Table-of-contents)


