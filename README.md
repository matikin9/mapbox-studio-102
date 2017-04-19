# mapbox-studio-102
Intro to Mapbox, OSM, and GitHub.

Style a map, add data to it, and then display it on a webpage and make it interactive with informational popups.

## Agenda

Time | Agenda |
------ | ----- |
6:30-7pm | <ul><li>Wait for people arrive.</li><li>Snack on pizza.</li></ul> |
7-8pm | **Mapbox Studio**<br><ul><li>Intro to Mapbox</li><li>Intro to OSM</li><li>Play with styling</li></ul> |
8-9pm | **Data & Webmaps**<br><ul><li>Load data into Mapbox</li><li>Intro to GitHub</li><li>Fork the repo and build a custom map</li><li>Advanced - add 3D building rendering</li></ul> |
 
 ## Repository Files
 This repository contains the webpage file that attendees will use to build their own map.
 
-File | Description |
------|-------------|
index.html | A basic webmap that you can use as a template for your own Mapbox Studio-styled map. |
index-adv.html | An advanced webmap that contains interactive popups generated from the dataset added to your Mapbox Studio-styled map. |
data/data-file.geojson | The raw .geojson data file we're using for the workshop |

## Instructions
### Preparation
1. Fork the [mapbox-studio-102](https://github.com/matikin9/mapbox-studio-102/) repository. You can also download the repo to your computer, by clicking the bright green button labeled "Clone or Download"

2. This workshop uses the following programs and requires free account signups.
   * [Mapbox Studio](https://www.mapbox.com/studio/) - An Application to build and design a map by using data from OpenStreetMap or add some of your own.
   * [Github](https://github.com/) - An online repository for digital projects with code and data. Our maps will be hosted through this website so you can leave with a web map to show your friends!

3. Text Editor - A program for writing code. Guess what? You get to learn a little coding on how to make your map even better, like adding popups or search by address! There are many editors, here are the most popular.
   * [Sublime](https://www.sublimetext.com/) for Mac and Windows
   * [http://brackets.io/](http://brackets.io/) for Mac and Windows

### Mapbox Studio
*Let's style our own map!*
1. Let's fire up Mapbox Studio on our web browsers. Let's check out what kind of features this tool offers with the [Mapbox Manual](https://www.mapbox.com/help/studio-manual/)
2. Did you know mapbox studio uses data from [OpenStreetMap](http://www.openstreetmap.org/) also known as OSM? OSM is pretty much a wikipedia of maps, all made by people and collaborators like you mapping communitiesa and the world.
   1. New to OSM?, check out the beginner's guide from [learnOSM](http://learnosm.org/en/). Soon you will be mapping your neighborhood, adding buildings, points of interest, etc.
3. Let's create a custom style! [Styling Steps](https://www.mapbox.com/help/create-a-custom-style/)
4. What if I have data I want to add? [Upload data to Mapbox](https://www.mapbox.com/help/uploads/)
   1. In this repo we have a geojson file (What's [geojson](http://geojson.org/)) of the buildings in Downtown LA. We can use this to upload to Mapbox. [LINK to file](https://github.com/matikin9/mapbox-studio-102/blob/master/data/downtownLA_OSM.geojson)
5. What if I want to create my own dataset and make my own points, lines or polygons?...oh my. | [Create a dataset](https://www.mapbox.com/help/add-points-pt-1/#create-a-dataset)

### Data & Webmaps
*Get the Code!*
1. Fork the [mapbox-studio-102](https://github.com/matikin9/mapbox-studio-102/) repository.
2. Turn on GitHub Pages.
   1. Go to Settings, scroll to the GitHub Pages section and select "master branch" for the Source.  Save!
   2. GitHub has now made your code live!  Click the link to see your site; save the URL to your repository's description so you can easily reach your site.
3. From the repository file list, click on "index.html", then click the edit (pen) icon in the upper right to edit the file.
4. Replace the tilelayer URL with YOUR custom styles - go to Mapbox Studio, select your style, and go to Share, Develop and Use.
5. Under Develop with this style, select Leaflet and copy/paste the displayed URL.
6. Commit your changes.
7. Visit the GitHub pages URL and see your custom map!  Styles may take several minutes to update with your dataset.

## History
Developed for a MaptimeLA workshop held on 4/19/17 in DTLA.
