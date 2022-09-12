# Green-index-google-map-python
Using google static maps API to get greenery index of any area in Python

A simple K-means clustering algorithm to get greenery index for any location baed on lat/long values.
The program can use user's prcise location as center of the 1 sqkm map and return a greenery score out of 100.
Very useful for map. weather and real-estate apps. These scores could be a component in determining livibility of a area.

- The code uses very basic K-means clustering with K value of 4. 4 clusters were found to resonate best each with roads, buildings, greens and field. 
- We applied rules to filter clsuter(s) closest to green RGB values.
- We use google maps static api with zoom value of 15 to get street level view. The preimeter is assprox 1sqkm.
- This can be further optimized by utilizing advanced color schemes (HSV etc.)
- Moving away from simple clsutering like k-means, application of deep learning can make the model more accurate.

Sample output from the code - 

![outout](https://user-images.githubusercontent.com/14168098/189573039-b58c5324-f170-47d0-8ff8-b47d4d2fef78.jpg)
