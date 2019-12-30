# Name
Interactive Map for Boulder County

# Description
Provides the Latino Task Force of Boulder County [website](https://latinotaskforce.squarespace.com) with an [interactive map](https://latinotaskforce.squarespace.com/new-page) that allows users to search for their zip code. If the zip code is found, the map is redirected and zoomed into the latitude and longitude. The marker at this location contains a pop-up that will inform users about elected officials, city boards & commission, and non profit boards & commissions. These categories link to a specific spot on the webpage. The interactive map was implemented using [Leaflet](https://leafletjs.com/) and [OpenStreetMaps](https://www.openstreetmap.org/#map=4/38.01/-95.84).

# License
[Leaflet](https://github.com/Leaflet/Leaflet/blob/master/LICENSE)
© OpenStreetMap contributors
[OpenStreetMaps](https://www.openstreetmap.org/copyright)

# Project Status
Data collection for the categories in marker pop-ups is in the process of being collected. The interactive map only finds zip codes classified as general, in Boulder County.  Latitude and longitude information for these zip codes is currently hard coded. A better approach as the data grows or more zip codes are requested to be implemented, is to store the data into a server and retrieve latitude and longitude information from it.
