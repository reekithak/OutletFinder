
# OutletFinder

### How the Initial coordinates are fetched?
- We're taking a map of entire chennai, and trying to find out the open and available outlets currently.
- Various categories such as Car wash, Medical Shops, Stationary etc have been added.
- We choose initial Corner Coordinates and Send them into the program, which finds out middle point in 4 different levels, hence covering a large area of space.
- The lines in "violet" are the ones we pass in (end coordinates), which are later connected and made into lines, which are later processed.
<img src="https://github.com/reekithak/OutletFinder/blob/master/images/outlet%201.JPG">



The Program is given a few end coordinates of a specific place. 
The algorithm calculates rest coordinates and covers the entire region around to create regional Clusters. 
The purpose is to use google API and find nearby stores ( useful in cases of a pandemic ) since it'll be pretty hard and dumb to go around and search for every single shop. 
A program just to find out the nearby outlets and sort them out according to the needs

( Work done as a part of internship at PI ) 


## Important Note:- 
- Replace the places with your email id's and API's respectively, You might want to subscribe for a pack / get a free trial for the google maps ( api ) 
