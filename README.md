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

File | Description |
-----|-------------|
index.html | A basic webmap that you can use as a template for your own Mapbox Studio-styled map. |
index-adv.html | An advanced webmap that contains interactive popups generated from the dataset added to your Mapbox Studio-styled map. |
data/data-file.geojson | The raw .geojson data file we're using for the workshop |

## Instructions
### Preparation
This workshop uses the following programs and requires free account signups.
 * [Mapbox Studio](https://www.mapbox.com/studio/) - An Application to build and design a map by using data from OpenStreetMap or add some of your own.
 * [Github](https://github.com/) - An online repository for digital projects with code and data. Our maps will be hosted through this website so you can leave with a web map to show your friends!

Text Editor - A program for writing code. Guess what? You get to learn a little coding on how to make your map even better, like adding popups or search by address! There are many editors, here are the most popular.
  * [Sublime](https://www.sublimetext.com/) for Mac and Windows
  * [http://brackets.io/](http://brackets.io/) for Mac and Windows

### Mapbox Studio
*Let's style our own map!*
1. Let's fire up Mapbox Studio on our web browsers. 
   1. If you are doing this from home, Mapbox has a [terrific manual](https://www.mapbox.com/help/studio-manual/) to follow and understand the basics.
2. Much of the data already provided on mapbox studio uses data from [OpenStreetMap](http://www.openstreetmap.org/) also known as OSM. OSM is pretty much a wikipedia of maps, all made by people and collaborators like you mapping communitiesa and the world.
   1. If you're unfamiliar with OSM, there's a beginner's guide from [learnOSM](http://learnosm.org/en/) which will get you started and soon you will be mapping your neighborhood, adding buildings, points of interest, etc.
Go to the Datasets tab and upload your geo data.
3. Select your dataset and Export to a new tileset.
4. Go to the Tilesets tab, select your tileset and add to a new style.
5. Go to the Styles tab and edit your map styles!

### Data & Webmaps
*Get the Code!*
1. Fork the [mapbox-studio-102](https://github.com/matikin9/mapbox-studio-102/) repository.
2. Turn on GitHub Pages.
   1. Go to Settings, scroll to the GitHub Pages section and select "master branch" for the Source.
   2. GitHub will give you a link which you can use to view your site.  Save it to your repository's description so you can see your code update immediately!
3. From the repository file list, click on "index.html", then click the edit (pen) icon in the upper right to edit the file.
4. Replace the tilelayer URL with YOUR custom styles - go to Mapbox Studio, select your style, and go to Share, Develop and Use.
5. Under Develop with this style, select Leaflet and copy/paste the displayed URL.
6. Commit your changes.
7. Visit the GitHub pages URL and see your custom map!  Styles may take several minutes to update with your dataset.

## History
Developed as a MaptimeLA workshop for 4/19/17.
