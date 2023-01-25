---
layout: default
carousels:
  - images: 
    - image: /assets/images/UeKatNavi/01.png
    - image: /assets/images/UeKatNavi/02.png
    - image: /assets/images/UeKatNavi/03.png
    - image: /assets/images/UeKatNavi/04.png
    - image: /assets/images/UeKatNavi/05.png
    - image: /assets/images/UeKatNavi/06.png
  - images: 
    - image: /assets/images/UeKatNavi/UeKatNaviCode/01.png
    - image: /assets/images/UeKatNavi/UeKatNaviCode/02.png
    - image: /assets/images/UeKatNavi/UeKatNaviCode/03.png
    - image: /assets/images/UeKatNavi/UeKatNaviCode/04.png
    - image: /assets/images/UeKatNavi/UeKatNaviCode/05.png
---
<!-- -->

## Description

This project was made as a part of the prototype towards my master's degree.

It is a proof of concept for Navigation module for an application that is meant to guide students through the process of getting the degree at our college.

It contains Navigation script that guides from one place to another and was put to work with one of the college's floors. 

Other parts of the application were not implemented in Unity, only as a functional prototype in Figma as we didn't have access to the college internal systems. 

This project left space for iBeacon navigation to be expanded in the future.

* * *

## Screenshots
  
{% include carousel.html height="50" unit="%" duration="9999" number="1" %}

Screenshots showcase proof of concept prototype at work with programmed UI elements. 

Last two are an alpha version of the prototype before we had access to the plans that we could then use to create 3D model of the college.

* * *

## Code Snippets

{% include carousel.html height="50" unit="%" duration="9999" number="2" %}

Code shows that for touch support there was a raycast used which checked what user had selected on screen.

The script either hid UI or changed data or changed materials to show User which room was selected.

It also shows how dropdown lists were filled by fetching data from the scene so it does not have to be done manually .

For navigation the best option was to use built in NavMesh instead of implementing shortest path algorithm like the Dijkstra's one.

* * *

## Github Link
[![GithubLogo](/assets/images/github-icon.svg) **Repository on github**](https://github.com/Yagami19/NaviApp)

Link leads to an external site.