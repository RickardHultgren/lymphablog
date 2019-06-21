---
layout: post
title: A first attempt to write a LYMPHA script for preeclampsia and employing it on LYMPHAonline
tag: gynecology
tag: acute
---

# A first attempt to write a LYMPHA script for preeclampsia and employing it on LYMPHAonline

## Introduction
Preeclampsia affects 2 to 8% of all pregnancies and is a leading cause of maternal and perinatal morbidity worldwide. Obesity, which is increasing at an alarming rate, is a risk factor for preeclampsia. Hence preparedness for patients with preeclampsia is of great importance.

One vulnerable population that has a greater risk of preeclampsia is young adolescents. Sometimes the patient might not be aware of the pregnancy. An effective screening strategy could be developed for preeclampsia through the LYMPHA language. Such a tool could even benefit the follow-ups of known pregnancies.

[LYMPHAonline](http://rickardhultgren.github.io/lymphaonline/index) is an online interpreter of the LYMPHA language. It is a beta-version, but could be tested as in desicion making support. A LYMPHA script for preeclampsia could be found on:
[https://github.com/RickardHultgren/LYMPHA-scripts/blob/master/preeclampsia.lympha](https://github.com/RickardHultgren/LYMPHA-scripts/blob/master/preeclampsia.lympha)
The script is based on the guidelines of the [swedish anestesiologist society](https://sfai.se/riktlinje/medicinska-rad-och-riktlinjer/.anestesi/preklampsi/). 

## Instructions
Go to the [LYMPHAonline](http://rickardhultgren.github.io/lymphaonline/index) webpage. It takes a while until the entire page is loaded. The screen is loaded when the home-button is orange. In the first box write 
~~~~
https://raw.githubusercontent.com/RickardHultgren/LYMPHA-scripts/master/preeclampsia.lympha
~~~~

Depending on the situation a healthcare professional could use the script in different ways. If the script should be employed as a screening tool before a visit at healthcare professional then write in the second box:
~~~~
screening.
~~~~
If on the other hand the script should be employed in connection with a visit, then write in the second box:
~~~~
meeting.
~~~~

In the third box write how many steps you want to go ahead in the script. If you just want to know what to do next, then write
~~~~
2
~~~~

![<img src="http://rickardhultgren.github.io/lymphablog/images/preeclampsia1.png">](http://rickardhultgren.github.io/lymphablog/images/preeclampsia1.png)

Then click on *Check for varialbe factors* and wait. After a while new boxes will appear. There is one box for each parameter that should go into the algorithm of the LYMPHA script.

After clicking implement variables in script, the script will be executed and a list of action should be shown.

![<img src="http://rickardhultgren.github.io/lymphablog/images/preeclampsia2.png">](http://rickardhultgren.github.io/lymphablog/images/preeclampsia2.png)
