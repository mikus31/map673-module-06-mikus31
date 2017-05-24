# Lab 06: Carto.js and MAP673 Final Map Planning

## Part I. Using Carto.js to make a dynamic web map

**Option #1 (4.5 pts)**

Using your own dataset hosted by CARTO, build a client-side thematic web map using the Carto.js `createLayer()` method, and a source object. The map type may be of any kind (choropleth, prop symbol, etc). And you may symbolize it as you wish.

Be sure to minimally include:

* a map title and description (One easy option is to create a div element (or two) and position it absolutely over the map and structure your heading, paragraph and/or list items within that div)
* any relevant metadata

Begin by copying the *lesson-06/index.html* file into your *lab-06/* directory, or building a new *index.html* file yourself from scratch within the *lab-06/* (this is good practice).

**Option #2 (5.5 pts)**

Extend what is covered in the lesson and above to include:

* A meaningful legend. The lesson doesn't cover this, but search CARTO's docs and consider how to include a legend in your map. Again, consult these [useful examples  for web mapping with Carto.js](https://github.com/CartoDB/carto-workshop/blob/master/06-sdks/exercises/cartojs.md)
* An interactive information window to retrieve specific information about map features. Consult the CARTO guide [Creating an info window with the createLayer() function](http://docs.cartodb.com/faqs/infowindows/#creating-an-infowindow-with-the-createlayer-function).

## Part II. Your final project's topic, objectives, and data (**2.5 pts**)

It's time to start thinking carefully about your final map project for MAP673. Using the process covered in Module 05, the deliverable for this week will include three pieces:

1. the **map topic** and/or geographic phenomena your map will explore
2. an articulation of the **map's objectives** and **user needs**
3. your **data source** and (at least a sample of) the data required to meet the map's objectives

Write thorough descriptions/answers to the following within a markdown file (e.g., *topic-objectives.md*) and commit to your map673-module-06-*username* repository.

If you're still head scratching for a good data/topic, consider exploring some of [these data sources](https://spatialreserves.wordpress.com/2017/01/29/a-top-10-list-of-useful-geospatial-data-portals/).

### 1. Topic and/or geographic phenomena your map will explore

What are you mapping? Briefly describe the topic and the geography the map intends to represent. Also, provide a tentative title (and possibly a subtitle) for you map. Remember that good titles, while being provocative and potentially fun, also tell a user three things: 1. what is being mapped, 2. where it's being mapped, and 3. when the phenomena occurred.

### 2. Map objectives and user needs

* Begin by answer the question,  "Why are you making this map?"
* Consider your own position with respect to the map and tell us why you are making it and what you want to get out of it.
* Create a brief user persona and tell us what this persona(s) will get out of the map. Why are they using it? How would you characterize this user in terms of their expertise and motivation (i.e., novice/public, average, expert/domain-specific)
* Imagine a scenario about how the user may use the map. It need not cover all potential use case scenarios, but it should describe some potential action the user will engage in to meet their objective (i.e., filtering the data, searching for an address, changing the attribute through a dropdown menu)

### 3. Data source

This one is really important. Sometimes we have great goals and ideas for a map. But if we can't (somewhat easily) get the data ... the map is going nowhere. I need to see that you have access to the data, or at least some ugly data that we can consider strategies for refining and cleaning up.

Provide me with 1. your anticipated data source (URL, etc) and 2. a small sample of the data (e.g., CSV, GeoJSON, Shapefile, link to a stable a database, screenshot of the data)
