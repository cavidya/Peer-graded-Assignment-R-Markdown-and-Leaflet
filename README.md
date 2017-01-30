# Peer-graded-Assignment-R-Markdown-and-Leaflet
## Coursera Project work 2017.01.29
Vidya Cuddalore Arivudainambi


library(leaflet)

m <- leaflet() %>%
  addTiles() %>%  
  # Specify coordinates for Damascus
  addMarkers(lng=36.278336, lat=33.510414, popup="War. War never changes.")
m  # Print the map
