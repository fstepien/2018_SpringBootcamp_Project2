### MaxShop - PSD Conversion 

[Live Link - maxshop.filipstepien.com](http://maxshop.filipstepien.com)

+ All click and hover drop downs in CSS and HTML only
+ Use a wrapper to constrain content on large displays
+ Use external .css files
+ box-sizing:border-box;
+ CSS Normalize
+ Floats and the proper use of .clearfix
+ Semantic HTML elements (header, footer, section)
+ Google web fonts
+ Relative positioning/absolute positioning
+ Background images
+ Links within the page
+ Icons made with icon fonts/css rather than PNG
+ Creative use of Borders and border radius
+ CSS3 animations 
+ Tested in Chrome, Firefox, Edge and Safari, Android Tablet, Android Mobile

![](http://maxshop.filipstepien.com/readme/maxshop-1.png)

###### HTML/CSS Dropdowns

Responsive Design with click and hover drop downs using CSS and HTML Only

![](http://maxshop.filipstepien.com/readme/1920.gif)

###### CSS GRID - Combining Repeat, Auto-Fit and MinMax 

`grid-template-columns: repeat(auto-fit, minmax(150px, 1fr) minmax(150px, 1fr));`

The code above works well in Chrome and allows products to resize and when required drop down two at a time. The same responsive break point can be achieved in firefox with media queries using:

`grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)`

Below are some twitter responses on this topic:

@Filip_Stepien: @FirefoxDevTools Wondering if there is a workaround for using minmax twice in grid-template-columns: repeat(auto-fit, minmax(150px, 1fr) minmax(150px, 1fr)); Currently crossed out in Firefox. Thanks.

@FirefoxDevTools: This looks like a grid implementation difference between Firefox and Chrome. Here's a test case: [http://jsbin.com/pojepohuwe/edit?html,css,output](http://jsbin.com/pojepohuwe/edit?html,css,output) … All items are in 1 column on Firefox (61), but in 3 columns in Chrome (65).
Maybe @CodingExon or @rachelandrew know?

@CodingExon I filed [https://bugzilla.mozilla.org/show_bug.cgi?id=1456504](https://bugzilla.mozilla.org/show_bug.cgi?id=1456504) … to follow up (but might rly be a Chrome bug if we're correctly forbidding that combination, per spec). @rachelandrew might be better able to address his request for workaround; I don't have grid paged into my head, & am just starting a vacation. :)

@rachelandrew: I think this is just the fact that Firefox doesn’t support a track listing there [https://github.com/rachelandrew/gridbugs#2-repeat-notation-should-accept-a-track-listing](https://github.com/rachelandrew/gridbugs#2-repeat-notation-should-accept-a-track-listing)

![](http://maxshop.filipstepien.com/readme/maxshop-2.png)

###### Browser Outline Implementation

`outline: white 5px solid;`

Chrome, Safari, and Edge place the outline on the edge of the parent div, while Firefox includes psuedo elements with position:absolute when placing the outline.

[More Details available at https://bugzilla.mozilla.org/show_bug.cgi?id=687311](https://bugzilla.mozilla.org/show_bug.cgi?id=687311)

![](http://maxshop.filipstepien.com/readme/maxshop-3.png)