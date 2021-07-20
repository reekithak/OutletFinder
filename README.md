
# OutletFinder

### How the Initial coordinates are fetched?
- We're taking a map of entire chennai, and trying to find out the open and available outlets currently.
- Various categories such as Car wash, Medical Shops, Stationary etc have been added.
- We choose initial Corner Coordinates and Send them into the program, which finds out middle point in 4 different levels, hence covering a large area of space.
- The lines in "violet" are the ones we pass in (end coordinates), which are later connected and made into lines, which are later processed.
<img src="https://github.com/reekithak/OutletFinder/blob/master/images/outlet%201.JPG">

### The Final Set of Coordinates ?
- After the initial Processing, the new set of coordinates are automatically calculated by the program, and taking it into a level of 4-5 within the new lines, hence by covering a huge area in space.
- and they're stored into lists matched by indices.
<img src="https://github.com/reekithak/OutletFinder/blob/master/images/outlet2.JPG">

### Covering the area?
- The next thing we do is fix a particular radius and trying to cover the entire area within our reach.
- We confirm the output by constructing a scatter map with the current input radius to see manually if it covers everything.
<img src="https://github.com/reekithak/OutletFinder/blob/master/images/outlet3.JPG">
The Program is given a few end coordinates of a specific place. 
The algorithm calculates rest coordinates and covers the entire region around to create regional Clusters. 
The purpose is to use google API and find nearby stores ( useful in cases of a pandemic ) since it'll be pretty hard and dumb to go around and search for every single shop. 
A program just to find out the nearby outlets and sort them out according to the needs

( Work done as a part of internship at PI ) 


## Important Note:- 
- Replace the places with your email id's and API's respectively, You might want to subscribe for a pack / get a free trial for the google maps ( api ) 
