# MSF_Alpha
Project: Aleviating the bottleneck

This application was designed to assist Misssing Maps project in mapping out areas which aren't currently mapped.

Abstract

Initialy the volunteers from the missing maps project had to manually enter in the data obtained in the field using a survey application called Open Data Kit (ODK). They entered this data into an offline mapping program by manually selecting nodes on the map and entering in the information for the tags. We designed our application to automate this process instead of them manually entering in the data.

Firstly, to make the future process much faster, easier and more efficient for the volunteers. We designed our program to convert XML files, which came directly from the survey form, which was filled out using the ODK application that they use in the field, to an OSM file that can then be directly opened from the offline mapping program, JOSM, that is then uploaded to Open Map Source.

Secondly, to unclog the backed up amount of data they would have collected already, our program convert excel files containing mass amounts of data to the OSM format to also to then be uploaded in a mass amount. 

Along with simply the nodes being added with the correct longitiude and latitude, the correct OSM tags are also automaticaly generated according to the information collected from the form automaticaly.

Summary,

This program converts XML, XLSX and XLS documents to the OSM format which is readable by JOSM.
Authors: Afshin Sabahi, Dylan Angus, Siddharth Chandrashekar.
