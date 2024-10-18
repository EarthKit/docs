---
title: Sift
---

[EarthKit Sift](https://earthkit.app/sift) is an interface for browsing through map, streetview, and satellite imagery of coordinates without losing track of your place in the list. 
It also supports enhancing the metadata of coordinates with AI -- think [Elicit](https://elicit.com/) but for geospatial data.

Sift is good for geolocation if you:
- Have a list of possible coordinates for an image
- Want to find the most likely coordinate for an image by either going through the images yourself or by asking the AI to help you


## How to use Sift to geolocate an image

{{% steps %}}

### Load the initial list of coordinates
You can either upload a CSV/JSON file with a list of coordinates, 
or import existing coordinates from an existing EarthKit tool such as [overpass turbo](https://earthkit.app/osm) or [streetview](https://earthkit.app/streetview).

![Import Coordinates](./images/EarthkitSiftImport.gif)

### Upload your image
![Upload Image](./images/EarthkitSiftUpload.gif)


### Iterate through the coordinates

Iterate through the coordinates, and match the satellite, streetview, and map imagery with your target image.

![Iterate through the coordinates](./images/EarthKitSiftLabel.gif)

### (Optional) Use AI to enhance metadata & sort

{{< youtube J_pja8AdjSc >}}

{{% /steps %}}
