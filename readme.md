# GPX und KML coordinate files for canyons from Descente-Canyon.com
Unofficial GPX und KML coordinate files based on the data from https://www.descente-canyon.com/ 

Use with care. Descente doesn't provide such files or make it easy to access the coordinates, and they will have their reasons for this. For me these files make planing more efficient, faster and safer. But 
please don't expect the coordinates to be right and rely on them.

The data is from 2019, but was still up to date in 2021, since the data hasn't been updated since the redesign (the necessary pages seem to be missing since the redesign).

[descente-canyon-summaries.kml](./descente-canyon-summaries.kml) (the points from the summary map with the summary table)  
[descente-canyon-summaries.kml](./descente-canyon-summaries-basic.kml) (the points from the summary map without the summary table, for apps that don't support html in the description)  
[descente-canyon-positions.kml](./descente-canyon-positions.kml) (points from the canyon detail maps, entries, exists, parking, etc.)  
[descente-canyon-positions.gpx](./descente-canyon-positions.gpx) (like the kml file, for apps that don't support kml)  

# App support
They files should work with almost every app, but not every app handles the large number of points well. They do work 
excellent with Locus Map on Android and probably OruxMaps (and a lot more). It is important to also import points with duplicate names (choose "ignore" with Locus), because the names are not unique. For example if a canyon has two entry coordinates.  

On Apple devices there is no app that comes even close to Locus or Orux. In my opinion Cartograph Pro is the 
only decent alternative to both Android apps, but is harder to set up and use. Maps.me seems to work ok and is probably easier to use.

# Changelog
* 10.2021: fixed detail position points with negative values
* 05.2021: added summary table to the summaries file
* 05.2021: added summaries-basic file for apps that don't support html or have problems with the bigger amount of data
* 05.2021: descente link now goes to the description, if a description exists (summary otherwise) 

# TODO 
* convince the descente creators that coordinate files are good thing, and that they should offer them on their site and implement the function for the users to add or update coordinates and canyons (this is missing since the redesign)
* better icons
* make the coordinate names unique (no mistakes on the import possible, also some apps might require them to be unique)
* fixes for different apps (?)
* you tell me

# Licence
CC BY-NC-SA 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/

* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* NonCommercial — You may not use the material for commercial purposes.
* ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
* No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Data is from https://www.descente-canyon.com/ and all their excellent committers, you rock! 

