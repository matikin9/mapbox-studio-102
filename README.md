# mapbox-studio-102
*An intro to Mapbox, OSM, and GitHub.*

Style a map in Mapbox Studio and then display it on a webpage!  Go advanced-mode by adding data to your map and then making it clickable with info popups!

## Agenda

Time | Agenda |
------ | ----- |
6:30-7pm | <ul><li>Wait for people arrive.</li><li>Snack on pizza.</li></ul> |
7-8pm | **Mapbox Studio**<br><ul><li>Intro to Mapbox</li><li>Intro to OSM</li><li>Play with styling</li></ul> |
8-9pm | **Data & Webmaps**<br><ul><li>Load data into Mapbox</li><li>Intro to GitHub</li><li>Fork the repo and build a custom map</li><li>Advanced - add 3D building rendering</li></ul> |
 
 ## Repository Files
 
 This repository contains the webpage file that attendees will use to build their own map.
 
 File | Description |
------|-------------|
`data/downtownLA.geojson` | The raw .geojson data file we're using for the workshop |
`webmaps/mapbox_basic.html` | A working sample of the basic map we'll create using DTLA building data. |
`webmaps/mapbox_popup.html` | A working sample of the advanced map we'll create.  It contains the DTLA building data as well as informational popups. |
`index.html` | The base webmap that we'll start with. |

## Preparation

1. This workshop requires free account signups for the following tools:
   * [Mapbox Studio](https://www.mapbox.com/studio/) - An Application to build and design a map by using data from OpenStreetMap or by adding some of your own.
   * [GitHub](https://github.com/) - An online repository for digital projects with code and data. Our maps will be hosted through this website so you can leave with a web map to show your friends!

2. Once you've got a GitHub account, fork the repository: [mapbox-studio-102](https://github.com/matikin9/mapbox-studio-102/). You can download the code to your computer by clicking the bright green **Clone or Download** button, or you can use one of the options below to edit code directly in the browser.

3. Code Editor - A program for writing code. Guess what? You get to learn a little coding on how to make your map even better, like adding popups or a search by address! There are many many editing options - here are some popular ones:
   * Local editing
      * [Sublime](https://www.sublimetext.com/) for Mac and Windows.
      * [Brackets](http://brackets.io/) for Mac and Windows.
      * [Atom](https://atom.io/) created by GitHub for Mac and Windows.
   * Browser editing
      * [Cloud9](https://c9.io) for developing directly from your browser.
      * [GitHub](https://github.com) for developing directly from your browser, in your GitHub repository.

## Workshop Instructions

### Part 1: Mapbox Studio
*Let's style our own map!*

1. Let's fire up Mapbox Studio in our web browser. Let's check out what kind of features this tool offers with the [Mapbox Studio Manual](https://www.mapbox.com/help/studio-manual/).

2. Did you know Mapbox Studio uses data from [OpenStreetMap](http://www.openstreetmap.org/), also known as OSM? OSM is pretty much a Wikipedia of maps, all made by people and collaborators like you, contributing their time to map their communities and the world.
   1. New to OSM?, check out the beginner's guide from [learnOSM](http://learnosm.org/en/). Soon you will be mapping your neighborhood, adding buildings, points of interest, etc.
   
3. Let's create a custom style! Read about [Mapbox Styling Steps](https://www.mapbox.com/help/create-a-custom-style/).  *Note: don't forget to Publish your style.*

4. What if I have data I want to add? Read about how to [Upload Data to Mapbox](https://www.mapbox.com/help/uploads/).
   1. In this repo we have a geojson file (what's [geojson](http://geojson.org/)?) of the buildings in Downtown LA. We can upload this geo data to Mapbox. [See the data here](https://github.com/matikin9/mapbox-studio-102/blob/master/data/downtownLA.geojson).

5. What if I want to create my own dataset and make my own points, lines or polygons?...oh my.  Read about how to [Create a Dataset](https://www.mapbox.com/help/add-points-pt-1/#create-a-dataset).

### Data & Webmaps
*Get the Code!*

1. If you haven't already, fork the [mapbox-studio-102](https://github.com/matikin9/mapbox-studio-102/) repository.

2. Turn on GitHub Pages.  GitHub lets you turn your repository into a LIVE site so you can show it to all your friends!
   1. Go to Settings and under the GitHub Pages section, select **`master branch`** for the Source.  Remember to Save - GitHub will then give your site a URL.
   2. GitHub has now made your code live!  Save the URL to your repository's description so you can easily get to your site.  Changes to your repository will now automatically show up on your website.
   
3. Time to show off your own map styles by editing the code with your favorite editor.
   1. If you want to just use GitHub in your browser, click the **`index.html`** file, and then click the edit (pencil) icon in the upper right corner.

4. You only need to make TWO code changes to show your styled map.  Go to Mapbox Studio and click the **`</> Share, develop & use`** link for your Style.

5. Under the **`Develop with this style`** section, you'll find values for the **Style URL** and **Access Token**.  Copy and paste these values to  **`index.html`**, where indicated in the code's comments.

6. Now you can update your repository files:
   1. Upload the files to your repository if you edited them locally.
   2. If you used GitHub, click the big green **Commit** button.

7. Visit your site and see your custom map!  If you make changes to your Mapbox Style, it may take up to 10 minutes to update.

### Bonus
*Click that map!*

1. Take a look at the **`webmaps/mapbox_popup.html`** file to add clickable popups to your map.

## History

Developed by [Omar Ureta](https://github.com/cityhubla) and [Nina Kin](https://github.com/matikin9) for a MaptimeLA workshop held on 4/19/17 in DTLA.

## How to Use

Anyone is free to fork this repo and hold their own local workshops on Mapbox Studio - if you do, you will want to update some of the links to point to your own repository!  We'd love to get feedback about your experience using the workshop, and we're always open to suggestions for changes (or bug fixes, haha).  You can contact us by opening an Issue in this repository, or by reaching out to us on Twitter.
