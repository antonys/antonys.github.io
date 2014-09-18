Exercise 1: Loading Data into QGIS
==================================

We'll start by loading some data into QGIS from a spreadsheet. Let's assume you have been sent some vulnerability analysis data, and you need to load it in order to carry out some analysis.

QGIS doesn't work directly with Excel or other spreadsheet files, but you can load CSV.

1. Download the source data from [] - this is vulnerability analysis data used by Unicef in the Democratic Republic of Congo.
2. With QGIS open, go to `Layer > Add Delimited Text Layer`, and select the data
3. You will see a screen like this [] - at this stage you can leave all the defaults in place and click `OK`
4. You have created your first map!

We'll now have a look at the data in a bit more detail.

1. Double-click on the layer name in the table of contents on the right-hand side.
2. You will see this screen [], which you can use to see the properties of the data, and, for example, add styling
3. Click on each of the options on the left to see what is available.
4. Click on the `Fields` button, and you will see a list of the columns from the CSV which you imported.
5. You will see that there may be some problems with some of them - for example the `Pop_1` column appears as `Text`, instead of an integer field.
6. This is because QGIS makes a guess at the datatype which it should use for each field when it imports it - in this case, because the data had a comma `,` in it, it decided (wrongly) that it was text.
7. This won't be a problem if you just want to display the data. However it will prevent you using the data for calculations, or to drive styling.
8. To fix this, open the data in a spreadsheet, and change the format of `Pop_1_1` to omit the commas. At the same time, change the format of the `Date1` field to YYYY-MM-DD - this will tell QGIS that it's a date field.
9. When you have done this, reload the data and have another look at the fields - the fields you have changed should now be showing correctly (if you didn't have time to make the changes, an updated version can be downloaded here []).
