---
title: Streetview Localization
---

Earthkit [streetview](https://earthkit.app/streetview) localization tool allow you to browse through streetview imageries of a region, and match them with your target image.

Note: this documentation page is a work in progress.

## Steps

{{% steps %}}

### Select a general region and a sample gap in the map view

![Select Region](./images/EKStreetviewSelect.png)

### Click `Fetch Streetviews`

After clicking this, EarthKit will sample a set of streetviews within the selected region and display them on the map.
Hover over the highlighted points to see the streetview thumbnail.

![Fetch Streetviews](./images/FetchSV.png)

### Optional: Upload Image & AI Matching

Optionally, upload your target image and `Run Similarity Search` to find the most similar streetview using the [EigenPlaces](https://github.com/gmberton/EigenPlaces) model.

{{% /steps %}}