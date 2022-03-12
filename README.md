# Module 11 Challenge: UFOs

## Overview
The purpose of this analysis is to compile a website with reported UFO sightings. Each of the sightings is reported by date, location (city, state, country), a brief description of the UFO, and a comment. The webpage allows for user input to filter the table of results as they wish, dynamically updating the table with the desired information.

## Results
Upon opening the website, a table is presented with all UFO sightings listed, as seen in figure 1.

### Figure 1: UFO sighting website with the full table information.
![Figure 1](Resources/Figure%201.png)

If a user wishes to limit the information based on a desired date, location, or description of the UFO, the user just needs to enter the filter criteria for the entries they wish to see. For example, if a the user would like to see information on UFO sightings in El Cajon, California on January 1, 2010, they simply need to enter 1/1/2010 in the date field, "el cajon" in the city field, and just to make sure this is El Cajon, CA, enter "ca" in the state field. The table will automatically be updated as in figure 2.

### Figure 2: UFO sighting website with filtered UFO sightings. In this example, the table includes only sightings in El Cajon, CA on January 1, 2010.
![Figure 2](Resources/Figure%202.png)

## Summary
While this website is useful to perform a basic search, it has its limitations. The table itself is based on a static dataset. Therefore, if the user would like more recent data, they will need to search elsewhere. In addition, the filters will not allow searching for sightings in more than one specified city at a time. For example, the user would not be able to able to search for sightings both in Fresno, CA and St. Louis, Missouri with a single search.

Future enhancements to the website would be welcome. One enhancement would be to update the data on the website through an automated API call directly to the source. This would allow up-to-date data to be presented on the website at all times. Another possible enhancement would be to allow more advanced filtering to allow the selection of multiple locations, or perhaps a range of dates. Yet another possible enhancement would be to allow the user to select individual records as they browse the table, and then allow the user to compile their selected rows in a new table. A third enhancement would be to add a "clear filters" button, which would allow each of the filter criteria to be cleared and the full table presented once again.