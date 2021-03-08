# Don’t Cut DC’s Lifeline to Mental Health - Review

![Cover Photo](img/cover.jpg)

*By Jerome Orille | 3/12/2021 | GEOG 458*

[Link to the project](https://storymaps.arcgis.com/stories/dc3529cc90394d93974744a067fce81f)

## Introduction

My favorite memories of my childhood include experiencing life with my brother and friends. My brother, friends and
I would always go outside to play football, then go back to indulge in video games and spend the rest of our night
arguing over who would win. These little experiences taught me the value of family and friends. Fast forward to today,
and those experiences are long gone. My friends all moved out going down their own separate paths. But worst of all,
my brother was recently diagnosed with ADHD. He is suffering from this condition and is having trouble studying and
focusing, which causes him to lose his appetite and struggle with daily activities in life. I cannot bear to see
someone so important to me being consumed by a mental health condition.

The project I am reviewing is an article called **Don’t Cut DC’S Lifeline to Mental Health**, by the District of
Columbia Health Matters Collaborative. My short anecdote proves the importance of mental health and how I believe
it needs to be addressed in many other projects. According to the project, the DC Health Matters Collaborative was
created in 2012, and houses hospitals in the District of Columbia. The project was created to **advocate for avoiding**
**cuts to the budgets of various healthcare providers in Washington DC**. There is also a need to **prioritize the mental**
**health of the residents of DC**. The goal of this project is to create a call to action and give equitable access to
mental health. The intended audience appears to be pointed toward healthcare authorities and the higher-ups of Washington
DC, because of the call to action provided in the project. The project is very educational as well, so anyone who wants
to learn more about mental health in Washington DC would benefit from this project as well.

## Project Features and Elements

The project is ultimately an **ArcGIS Storymap** that is accessed by scrolling down an HTML page. The page contains text,
images, videos and ESRI maps. The images are graphs and maps that are shown on the page. The text describes the goal
of the project, the research done and what data was collected. The videos give an understanding of the problem of
mental health and why mental health needs more resources. The webpage uses many javascript functions. Javascript
functions are mainly used to present the elements on the page one by one. They are also used for showing tilesets of ESRI maps.

The web maps in the webpage usually only have two web map elements, which are sources and data points. Figure 5 shows an
additional element, which is a north arrow. The creators of the web maps are not using all of the cartographic elements,
which gives me a limited view of the maps they present. It would especially help to have a legend, because the variables
being measured may not be easy to understand if one just looks at the maps.

I also examined the metadata of the project. The author of the project was the **District of Columbia Health Matters**
**Collaborative**. I scoured the web for sources pertaining to this organization, and [found this website](https://www.dchealthmatters.org/).
Based on the information presented on the website, the organization seems to be trustworthy and benevolent,
showing care toward their works and staying true to their beliefs. The data sources used in the project are as follows:
- [Centers for Disease Control and Prevention WONDER](https://wonder.cdc.gov/)
- [Division of Population Health](https://www.cdc.gov/populationhealth/index.html)
- [National Center for Chronic Disease and Prevention](https://www.cdc.gov/chronicdisease/index.htm)

These are reputable sources because they are all from the **Centers for Disease Control and Prevention**.
The study was conducted in 2019, which assumes that the data started being collected in that year or even before.

## System Architecture

The project mainly utilizes **HTML, CSS and javascript** to present the information. HTML encompasses the entirety of the
project, as the webpage is built with HTML. CSS is used to stylize the elements further by introducing elements such
as text blocks, differing text colors and differing margins (see Figure 1). Javascript functions are used in a variety
of ways in the webpage, such as loading in tilesets.

Since the project is intended as a presentation to show a cause, the clients are the end users who read the information.
The server is stored on storymaps.arcgis.com as an ArcGIS Storymap, as the website is hosting the created Storymap.
The services used include various ESRI javascript functions, tilesets and Storymap functions used to create the webpage.
These javascript functions are mainly the data flowing in and out via requests; as the user scrolls down the page, more
requests will be made and more data will flow in. The data comes from ArcGIS, which includes basemaps, widgets and tilesets.

In the source code, there are many <div> tags (see Figure 2). An important tag is the ID “storymaps-root” which contains the
entire body of the Storymap. Removing this would cause the Storymap to disappear. The ID “next” contains the ID “storymaps-root”,
yet I am not sure what it is used for. I would assume that there are different CSS stylizations. Many <div> tags were created
below the ID “storymaps-root”, which seem to be various tilesets of the maps.

![Example of CSS Margin Formatting[(img/css.png)
*Figure 1: Example of CSS Margin Formatting*