<div class="section-inner sectionLayout--insetColumn">
<h2 name="fdbd" class="graf graf--h2 graf--leading">
<strong class="markup--strong markup--h2-strong">The Business Problem&#8202;—&#8202;Description:</strong></h2>
<p name="ca01" class="graf graf--p graf-after--h2">
For this project, I am going to utilize the Foursquare API for referencing 
<strong class="markup--strong markup--p-strong">location data in the Boston, MA</strong> area.
This data will allow us to report on and provide feedback to interested parties 
<strong class="markup--strong markup--p-strong">looking to open a bar</strong>.</p>
<p name="9c9a" class="graf graf--p graf-after--p">Boston, MA is a very popular city when it comes to nightlife and 
entertainment as well as its ratings for recommended bars and pubs. With this in mind, 
I would want to <strong class="markup--strong markup--p-strong">identify all of the locations that are not overly 
crowded</strong>, in terms of the <em class="markup--em markup--p-em">number of bars and pubs</em> 
(this may setup a new hot-spot location for more bars to follow). BUT, I want to remain in a popular 
tourist area as to not stray from high traffic neighborhoods.</p>
<p name="ee85" class="graf graf--p graf-after--p">
With the use of Python and its vast amount of Data Science libraries, I can accurately predict where to set-up 
shop for a new bar (or at least recommend).</p>
<h2 name="24c2" class="graf graf--h2 graf-after--p">The Data</h2>
<p name="7ed6" class="graf graf--p graf-after--h2">Following the Business Problem, the data necessary to achieve 
accuracy will need to account for situations and factors such as:</p>
<ul class="postList">
<li name="d00f" class="graf graf--li graf-after--p">Demographic information, e.g. population, density, education, 
age, income</li>
<li name="2ee1" class="graf graf--li graf-after--li">Number of tourist attractions in the neighborhood 
and/or nearby</li>
<li name="6356" class="graf graf--li graf-after--li">Number of existing bars in the neighborhood
and/or nearby</li>
<li name="7a32" class="graf graf--li graf-after--li">Total traffic in the different neighborhoods (more populated 
the better)</li>
</ul>
<p name="3a94" class="graf graf--p graf-after--li">I am going to stay within a certain radius of the city center, 
for defining our neighborhoods in a grid-like fashion:</p>
<ul class="postList">
<li name="629f" class="graf graf--li graf-after--p">Centers of potential locations will be generated with the use
 of algorithms and approximate addresses of the potential centers</li>
 <li name="f13f" class="graf graf--li graf-after--li">Center locations will be obtained using 
 <strong class="markup--strong markup--li-strong">Google Maps API reverse geocoding</strong>, and the use of 
 <strong class="markup--strong markup--li-strong">Google Maps API geocoding </strong>for obtaining location 
 coordinates.</li>
 <li name="ae03" class="graf graf--li graf-after--li graf--trailing">The number of bars and their 
 type/location in every neighborhood will be obtained using <strong class="markup--strong markup--li-strong">Foursquare
 API</strong></li>
 </ul>
 </div>