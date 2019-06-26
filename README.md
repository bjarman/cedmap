# cedmap
<img src="http://foraldravralet.se/parentsforfuture/wp-content/uploads/2019/03/p4f_logo_sev2_nobkg.png" width="200">

This is a very simple "hack" made for [Parents for Future Sweden](http://parentsforfuture.se/) to visualize which municipalities in Sweden: 

 - Has declared climate emergency
 - Has an ongoing discussion about declaring climate emergency
 - Has none of the above

The map uses [Leaflet JS](https://leafletjs.com/) together with GeoJSON from [Kodapan](http://kodapan.se/geodata/) to display Sweden and it's municipalities. The GeoJSON data includes contact details and population for each  municipality. 

The map also fetches a curated Google sheet that holds information about each municipals Climate Emergency Declaration status and any link to ongoing discussions where citizens can sign petitions etc. 

This "application" relies on a few external scripts and data files to function:

 - [Leaflet JS](https://leafletjs.com/)
 - [Kodapan](http://kodapan.se/geodata/)
 - [jQuery](https://jquery.com/)
 - [js-socials](http://js-socials.com)
 - [Font awesome](https://fontawesome.com/)
 - [Select 2](https://select2.org/)

Appart from these dependencies this is a very basic implementation, quick & dirty if you will. There is a lot of room for improvements and I welcome any climate/code activist to fork it and change it to suit the needs in your country.

The Google sheet holding the Climate Emergency Declaration status of Swedish municipalities is curated by crowd sourcing, i.e. we who are active in Parents For Future Sweden all search and investigate each municipality from time to time to update the sheet with new information. 

User Experience
The cedmap has the ability to show the map with a default color. Each municipality is shown either in the map default color, if we have no information on Climate Emergency Declaraion status, or in yellow if status is "ongoing process" or in green if the municipality in fact has declared Climate Emergency.
