## Table of contents

* [Overview](#overview)
* [User Guide](#user-guide)

## Overview

![ci-badge](https://github.com/wavecache/sharkbreaks/workflows/wave-cache/badge.svg)

WaveCache is a project designed to list and categorize various beaches and Surfbreaks around UH Manoa and Oahu.  The breaks could be listed by distance from campus, by skill level, wave direction (lefts or rights), ideal swell directions, and ideal swell sizes.  This app could be helpful for the students who have come to UH Manoa from other places and would like to know which beaches would be ideal to surf for their skill level.  Maybe we could include potential hazards as well and a basic descirption of the location.  We could also add additional information to the app such as other activities that could be done at the beaches, such as swimming, snorkeling, volleyball or scuba diving.  We plan on having two roles, an administrative role as well as a basic user role.  Users can view the places while admins can make changes.  Different tabs could be used to reflect different skill level or other categories.  A user can specify skill level and get various suggestions based on their skill level.  User logs in, sets up profiles and can browse or receive suggestions.  We could also implement a rating system where users can rate the breaks.  Depending on how far we get maybe some beyond the basics features could be implemented, user generated reviews of places or maybe a chat area where people can discuss.

The current mock up can be found <a href="https://studntnu-my.sharepoint.com/:b:/g/personal/lassetw_ntnu_no/ER4MvZZXC5VJkEwnQwLg744BxYV8sqoXK-FxqbB4tIq1rw?e=dQj4tf">here</a>.

The GitHub organization associated with this project and all of its repositories can be found at <a href="https://github.com/wavecache">this link</a>.

Our first project board, M1, can be found <a href="https://github.com/wavecache/sharkbreaks/projects/1">here</a>.
  
Our second project board, M2, can be found <a href="https://github.com/wavecache/sharkbreaks/projects/2">here</a>.

Our third project board, M3, can be found <a href="https://github.com/wavecache/sharkbreaks/projects/3">here</a>.

## Deployment

The site is located at <a href="http://www.wavecache.surf/#/">Wave Cache</a>, come join us! 

## User Guide

This section provides a walkthrough of the Bowfolios user interface and its capabilities.


### Landing page

This page will have the navbar, a surfing background and some basic welcoming info about the site.
The following is a current screenshot of our Landing Page.
![Picture of the landing screen](/Images/LandingPage11-18.png)


### Sign in page

Where returning users sign in.


### Sign up page

Where new users sign up.
<a href="http://www.wavecache.surf/#/signup">Here</a>

<img src="/Images/Register.JPG">



### Friends list

Where you can see the contact info of people you've talked to before.
![Picture of the landing screen](/Images/friendsPage11-18.png)


### List of breaks

![Surf Breaks](/Images/SBPage.png)

A list of all the breaks in the system. If you are logged in, you are able to add a new break. In addition you can edit the breaks made by yourself. By clicking on the card title, it takes you to the surf break page.

### Add surf break page

Add a surf break if logged in. The changes is sent to the Mongo database and updated throughout the app. 

![Surf Breaks](/Images/addPage.png)

### Edit surf break page

Edit a page made by the logged in user. The changes is sent to the Mongo database and updated throughout the app. 

![Surf Breaks](/Images/editPage.png)


### Page for each Break


![Surf Break Page](/Images/surfBreakPage.png)

Each break will have its own page with all the information known on it, as well as an overview of the friends who have liked the break.

Currently the page can get information about the break from the Mongo data base. It is also fetching data from an API every 10th second. The like fuctionality is missing, but will be implemented once the friends list fuctlionality is done. 


### Public forums board

Public exchange of ideas, where there will be a list in order of recency, of all the threads of conversation people have about things like the best beaches, best beaches for new surfers, meetups and whatever else people want to talk about.


### Page for each public forum

Each discussion will have its own page.


### Admin homepage

The page where admins can see all of the information across the site, such as users, activity etc.

## Developers

### Quinn Bianchi-Lawson

A computer engineering student at UH CoE, Quinn is scheduled to graduate in Spring 2022.

### Constantine Peros

Constantine is an ICS student, interested in game development, AR, VR, Cryptocurrency, Robotics, and Surfing.

### Chase Miyasato

Chase was born and raised in Hawaii and has been surfing from a young age.

### Lasse Wardenær

Lasse is a graduate student doing an MSc in control engineering.

-----
