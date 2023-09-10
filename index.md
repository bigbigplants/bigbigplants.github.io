
# Introduction

So, you want to grow plants?

This document contains my lab notes for a hobbyist/amateur botany project. This project’s aim is to establish and construct optimal growing conditions for a range of plants, with the ultimate achievement being the growth and propagation of rare and exotic species. A side quest of this project is to establish these conditions in as low-cost a way as possible, and as efficiently as possible.

In order to control the growing environment more precisely, I’ll be using a hydroponic setup. This means I can precisely control all variables relating to the plant’s growth, including specifics of their nutrient intake.
I'm also approaching this topic as an **absolute beginner**, with essentially no experience in organic chemistry, biology, or any agricultural experience.
I do however have a background in academic research, so will be applying my research skillset to these problems, to hopefully achieve optimal solutions as quickly as possible.

**Chapters**
<ul>
  {% for chapter in site.chapters %}
    <li>
      <a href="{{ chapter.url }}">{{ chapter.title }} <span class="right">({{ chapter.date }})</span></a>
    </li>
  {% endfor %}
</ul> 

* Do not remove this line (it will not be displayed)
{:toc}


## Useful Tools

Before we get into some plant specifics, I wanted to link to some useful tools for research and knowledge discovery which I've used in these notes;

|[connectedpapers.com](https://www.connectedpapers.com/)|Provide one paper and find related research papers|
|[diagrams.net](https://diagrams.net)|Diagram drawing software, useful for schematics|
|[Google Scholar](https://scholar.google.com/)|Search engine for academic papers|

**Fahrenheit/Celcius Reference**

|Fahrenheit|Celcius|
|----------|-------|
|32|0|
|50|10|
|69.8|21|
|86|30|
|98.6|37|


# Software
Configuring a hydroponics system to run automatically is possible using only hardware control switches. However, in order to gain some visibility into the health of the system, and to allow more fine-grain control over the parameters, additional software is required.
This software periodically checks the levels of different parameters by reading data from sensors, and then reacts to the values retrieved from these sensors by turning on fans, adding nutrients, and so on. These reactions to the sensor readings can be 


## Reactive Controllers

## Coordinators

## Data Storage
Each of the reactive controllers, whilst recording measurements from sensors and acting accordingly, may additionally send their measurements for storage and analysis.


# Outstanding Questions
which light specifically can be used in photosynthesis and why?

# References

{% bibliography --cited %}

