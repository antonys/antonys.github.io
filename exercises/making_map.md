Exercise 5: Making a Map
========================
When you are happy with the way your map looks, you can export it to a printable or viewable form.

## The Quick Way
The quickest way of doing this is to save what you can now see in QGIS as an image - this will allow you to print it, include it in a report, send it by email, etc.

To do this:
1. Go to `Project > Save as Image`, select a file type in the bottom right of the dialogue, and enter a file name.
2. An image will be created of the current view of the map in the right-hand QGIS panel.

## The Proper Way
What you have created may be enough, but it is very basic - it has no title, legend, scale, north arrow etc. If you want to add all these things, you will need to use the *Print Composer* - this is a dedicated layout engine within QGIS which will help create a map with all the appropriate additions.

This tool takes a little getting used to - but once you have mastered it, you will be able to produce high-quality standalone maps.
1. Go to `Project > New Print Composer`, then click `OK' to auto-generate a title
2. Add a map to the blank canvas - click the `Add New Map` button in the toolbar, then click and drag in the canvas to create a frame for the map.
3. When you release the click, the current map view will appear in the frame
4. If you want to change this view, you will need to change the setting so that your zoom and pan controls are applied to the content of the frame, not the frame itself
5. Click the `Move Item Content` button in the toolbar
6. Click and drag the map, and zoom in and out, to change the view which appears in the frame
7. Add some more items to the map using the toolbar - for example a legend and a scalebar
8. When you are done, click one of the `Export as` buttons (`Image`, `SVG`,`PDF`) to create an exported view of the map, then open it to admire your work
9. Close the Print Composer window - your map settings will be saved in the project using the name of the Print Composer.

