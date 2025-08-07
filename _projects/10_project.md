---
layout: page
title: DIPS
description: A teach demonstrator teaching note assessing the accuracy of GPS Logger app 
img: assets/pdf/techdemgl/cover.png
importance: 3
category: software
---

### ℹ️ About the Tech Demonstrator (Teaching Note)

This was a small project that I did to assess how the te GPS Logger app compares with Garmin GPS receiver. The purpose was to create a field class for students to compare how the app fares ***without Internet connectivity***. The question that I wanted my students to answer was  this: As GPS receivers are expensive, could a smartphone app be used to collect location data with reasonable accuracy that could facilitate the following use cases (indicative list): 

1. Collect ground truth for accuracy assessment of classified satellite imagery
2. Mapping of new roads or areas
3. Collecting waypoints of points of interests (in Environmental Impact Assessment (EIA) studies, Wildlife studies, mapping pollution discharge points, solid waste management locations etc.)
4. Basic Elevation survey of an area

For the app to qualify for such work, the following criteria were fixed:

1. The app should be free (preferably open source) 
2. Should not have ads
3. Should *not* collect personal data or share it with any third party
4. Should provide unlimited collection of points and tracks
5. Should provide unlimited export of waypoints and tracks in CSV, GPX and KML formats which can be imported in popular GIS applications. 
6. Should be reasonably accurate in the field without internet connectivity
7. Should provide elevation data with Geoid corrections 

The GPS Logger app by [BasicAirData](https://basicairdata.eu/projects/android/android-gps-logger/) met ***all of these*** criteria! 

This tech demonstrator teaching note documents a small exercise done n 2017 to answer how this app compares with a standard hand held GPS. It has detailed commentary on elevation and elevation correction that should significantly add to the understanding of students about vertically accuracy - a topic that is not substantially discussed while describing the accuracy of a GPS device. The idea was not to replace a GPS device but to add a free tool that can also be used to collect field data. 

I am sharing this note to aid teaching in GIS courses where course instructors can model an exercise on this teaching note. Students can be divided in groups and they can independently carry out this exercise and present their assessment to the class. 


***

### 📋 Read the Teaching Note Online 

👉 [Read the Teaching Note Online](/assets/pdf/techdemgl/index.html)

***

### ⤵️ Download the Teaching Note as PDF

👉 [Read the Teaching Note Online](/assets/pdf/techdemgl/techdemgl.pdf)

### ▶️ Video Tutorials - Using the GPS Logger App

You can learn how to use GPS Logger app with these video tutorials. The 2025 update video specidically covers the new interface updates while the older video also has some intresting information about the app that is still valid. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://youtu.be/MexKduwnCjw" class="img-fluid rounded" %}
        <div class="caption">
            ▶️ GPS Logger App 2025 Update 
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://youtu.be/YPHE8du-1jA" class="img-fluid rounded" %}
        <div class="caption">
            ▶️ GPS Logger App Old Video (has some good information)
        </div>
    </div>
</div>


***
 
ℹ️ *Note: This was just a preliminary project to create an exercise for students. More work might be needed in different locations and cover conditions to conclusively compare the two devices.*

