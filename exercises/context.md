Exercise 4: Adding Context
==========================
Let's assume that you are happy with your styled data, and with the query you have run, so you want to make a map for printing.

However before we do that, we're going to add some more data so that you can produce a map with some context, rather than just a collection of points on a page.

We'll do this by loading two additional sets of data:
1. A set of polygons representing the provinces in DRC
2. A background layer using OpenStreetMap to show settlements, roads etc.

To do this:
1. Download and save the file containing the DRC provinces from [https://github.com/antonys/antonys.github.io/blob/master/downloads/drc_provinces.zip](https://github.com/antonys/antonys.github.io/blob/master/downloads/drc_provinces.zip) - as before, right-click on `Raw` and `Save as`. This is a zip file, so you will need to unzip it first.
2. Click the `Add Vector Layer` button in the toolbar and navigate to the file you have downloaded, then add it to your map.
3. You'll see that the layer you have been working on until now has disappeared... this is because the new layer has gone straight to the top of the list, so it's obscuring everything else
4. To fix this, drag and drop the layers so that your ActivityInfo layer is at the top
5. Configure some styling to the new Provinces layer, to replace the default which QGIS has applied (don't worry to much about what it looks like for now)
6. When you have done this (and assuming you have the OpenLayers plugin installed, and an Internet connection), go to `Web > OpenLayers plugin > OpenStreetMap > OpenStreetMap`
7. This may take a little time to load, but when it's done you will have a ready-made background map.
8. Again, drag and drop the layers to get the right ones at the top, and try some of the other OpenLayers backgrounds to see how they look



