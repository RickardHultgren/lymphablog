---
layout: post
title: LYMPHA App
tag: app
---

## LYMPHA app

The shortage of health care professionals that I have mentioned previously ([Patient autonomy and medical algorithms](https://rickardhultgren.github.io/lymphablog/2021/12/09/Patient_autonomy_and_medical_algorithms.html)) affects mainly the low-middle income countries. One of the key concerns is severe skills shortages, where technology can be used to help empower lesser tiered workers. In these settings, low-cost phones and tablets, typically Android, are the platforms of choice. Therefore I develop an Android app for that shows what procedure would be appropriate to execute in a certain situation:
[https://github.com/RickardHultgren/lymphaapp](https://github.com/RickardHultgren/lymphaapp)

The app is in a rough alpha stage, but I hope you can get an idea of how the final app should work. The app loads a LYMPHA script. Then each node from the script is displayed as a screen, one at a time. In order to go to the next screen you have to click *OK*. There is an examle script inside the program with two nodes: *crepitation* and *antibiotics*. When you start the app reads the script and then this will be shown on your screen:

![<img src="https://raw.githubusercontent.com/RickardHultgren/lymphablog/gh-pages/_posts/images/lymphaapp1.png">](https://raw.githubusercontent.com/RickardHultgren/lymphablog/gh-pages/_posts/images/lymphaapp1.png)

The second screen:

![<img src="https://raw.githubusercontent.com/RickardHultgren/lymphablog/gh-pages/_posts/images/lymphaapp2.png">](https://raw.githubusercontent.com/RickardHultgren/lymphablog/gh-pages/_posts/images/lymphaapp2.png)

Do you want to test the current version? Then just download Kivy: 
[https://kivy.org/#home](https://kivy.org/#home)
