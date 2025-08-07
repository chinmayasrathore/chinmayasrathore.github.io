---
layout: page
title: Tech Demonstrator - GPS Logger App
description: A tech demonstrator teaching note assessing the accuracy of the Android GPS Logger app 
img: assets/pdf/techdemgl/cover.png
importance: 3
category: software
---

### ℹ️ About the Tech Demonstrator (Teaching Note)

This was a small project that I did to assess how the the GPS Logger app compares with a standard hand held Garmin GPS receiver. The purpose was to create a field class for students to compare how the app fares ***without Internet connectivity*** in collecting waypoints and tracks. The question that I wanted my students to answer was this: *As GPS receivers are expensive, could a smartphone app be used to collect location data with reasonable accuracy? Also, could the app facilitate the following use cases (indicative list): 

1. Collect ground truth data for accuracy assessment of classified satellite imagery.
2. Mapping of new roads or undocumented areas of interest (like plantations,agricultural fields etc). 
3. Collecting waypoints of points of interests (for Environmental Impact Assessment (EIA) studies, Wildlife studies, mapping pollution discharge points, solid waste management locations etc.).
4. Conducting basic elevation survey of an area

For the app to qualify for such work, I fixed the following criteria:

1. The app should be free (preferably open source). 
2. It should not have ads.
3. It should *not* collect personal data or share it with any third party.
4. It should provide unlimited collection of points and tracks.
5. It should provide unlimited export of waypoints and tracks in CSV, GPX and KML formats. 
6. It should be reasonably accurate in the field and work without internet connectivity.
7. It should provide resonably accurate elevation data with Geoid corrections.  

The GPS Logger app by [BasicAirData](https://basicairdata.eu/projects/android/android-gps-logger/) surprisingly, met with ***all of these*** criteria! 

This tech demonstrator teaching note documents a small exercise done in 2017 to answer how this app compares with a standard hand held GPS for field surveys. The note also has detailed commentary on elevation and elevation correction that should significantly add to the understanding of students about vertically accuracy - a topic that is not discussed in much detail while describing the accuracy of a GPS device. The idea of this exercise was not to replace a GPS device. Instead it aimed to explotre the possibility of adding a free tool that could also be used to collect field data in case GPS devices were not available. 

I am sharing this note to aid teaching in GIS courses where course instructors can model an exercise on this teaching note. Students can be divided in groups and they can independently carry out this exercise and finally present their assessment to the class. 

***

### 📋 Read the Teaching Note Online 

👉 [Read the Teaching Note Online](/assets/pdf/techdemgl/index.html)

***

### ⤵️ Download the Teaching Note as PDF

👉 [Read the Teaching Note Online](/assets/pdf/techdemgl/techdemgl.pdf)

### ▶️ Video Tutorials - Using the GPS Logger App

You can learn how to use the GPS Logger app with the following video tutorials. The 2025 update video specidically covers the new interface updates while the older video has some useful information about the app that is still valid. You can watch both these videos. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/watch?v=MexKduwnCjw" class="img-fluid rounded" %}
        <div class="caption">
            ▶️ GPS Logger App 2025 Update 
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/watch?v=YPHE8du-1jA" class="img-fluid rounded" %}
        <div class="caption">
            ▶️ GPS Logger App Old Video (has some good information)
        </div>
    </div>
</div>


***
 
ℹ️ *Note: This was just a preliminary project to create an exercise for students. More work might be needed in different locations and cover conditions to conclusively compare the two devices.*

