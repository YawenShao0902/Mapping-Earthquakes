# Mapping-Earthquakes
Module-14

**Overview**

The purpose of this challenge is to use HTML, JavaScript, and CSS to create earthquake maps and overlay them on top of eachother. Ideally we are creating three different maps that can have three different overalays. The overlays will be earthquakes, tectonic plates and then earthquakes with a magnitude greater than 4.5.

**Process**

First thing we did was added two different views to the map; streets and satelites. For each of the layers, all earthquakes, tectonic plates, and earthquakes with a magnitude of 4.5 or greater we followed the same strucutre on adding the information. We added the data using d3.json(), geoJSON(), and then added that to the allEarthquakes, tectonicPlates, and majorEarthquakes layers and then added that layer group to the map. 

![Screen Shot 2023-03-01 at 11 31 37 PM](https://user-images.githubusercontent.com/118235205/222362350-ee29a4dd-b0b8-4197-b1b6-9b8e1e6fbd23.png)

![Screen Shot 2023-03-01 at 11 31 48 PM](https://user-images.githubusercontent.com/118235205/222362546-984517dc-c162-4012-ab3a-aa23171bfc21.png)


![Screen Shot 2023-03-01 at 11 32 01 PM](https://user-images.githubusercontent.com/118235205/222362663-918a2b3d-4992-4903-925d-f721e55f3718.png)

![Screen Shot 2023-03-01 at 11 32 15 PM](https://user-images.githubusercontent.com/118235205/222362675-f05d40dd-bf61-4af7-aacb-dc234efcb960.png)

![Screen Shot 2023-03-01 at 11 32 24 PM](https://user-images.githubusercontent.com/118235205/222362694-433d5c13-a4a8-489b-aa98-4f084c1ea931.png)

To add an aditional map I added a dark style, using the same style of code as when adding the street and satelite view. 

![Screen Shot 2023-03-01 at 11 35 33 PM](https://user-images.githubusercontent.com/118235205/222362717-2c4215f7-6268-40b3-a6ec-7b49920b7f03.png)



**Analysis** 

As we can see from the Map that most earthquakes are concentrated around tectonic plates which is reanable to assume is correct based on teh basic knowledge of how earthquakes happen. 

![Screen Shot 2023-03-01 at 11 35 56 PM](https://user-images.githubusercontent.com/118235205/222362763-7432cc0a-7095-4667-ae47-8818134b98c5.png)

