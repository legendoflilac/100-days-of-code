# 100 Days Of Code - Log

### Recap of 100 Days of Code / Winter of Code

My goals for this challenge were to create a commitment to coding, work on personal projects, improve my coding ability, and complete the Front End Libraries and Data Visualization portions of the freeCodeCamp curriculum. 

Committing to coding was hard at times, but generally when I sat down to learn or work on my projects I appreciated the time well spent. Some days it felt like I knew nothing and that I wouldn't be able to get out of a rut, but eventually I would either read an explanation or solution, research for the right tools, or fix mistakes in my code that would put me back on the right path. 

I only just started working on a personal project with the IPERS data, inspired by the visualization of the counties of Iowa in the report. I'm glad I worked on a similar project first so I had some background with working with D3 and TopoJSON. I have more ideas for future projects as well as a result of doing this challenge.  

Naturally, I've improved my coding ability by working on these projects. While I wouldn't say I developed the best algorithms or solutions to some problems, I learned to stop blaming the curriculum for not teaching certain skills and instead developed a curiosity and problem-solving mindset that involved a mix of testing out my own theories and reading other's code for insight. 

I completed the Front-End portion just before the half-way point of the 100 days, and the dataviz portion largely took up the rest of it, with some time at the end for my personal project.

Not everything I did was aligned with the spirit with which the 100DoC program was created. I took a much more liberal approach to the idea by allowing time looking at tutorials, reading articles about code, and reading other people's code to count towards my hour of work per day. I also didn't connect with others through social media like the challenge suggests. I may try to integrate the social aspect more in the future.

Overall, I'm pleased with the experience and look forward to continuing to work on my skills.

### Day 100: February 4, 2020

**Today's Progress:** Day 100 ends in an accomplishment--I got the color scale to finally do something on my choropleth map! I switched back to a threshold scale since the quantile scale was breaking the data up into groups that didn't allow for much color variation. Of course, this was after figuring out the way I was connecting the map data to the benefit data was throwing errors. One bug occured specifically on O'Brien County, which I had mistakenly put a different type of apostrophe on, leading the function I was using to return as undefined. Additionally, instead of using the method of filtering the data array for the objects I needed, I looked on StackOverflow to find other solutions using the `find` method. I also researched a regex to separate the large amounts of money with commas in the tooltip.

**Thoughts:** I was determined to make some real progress with this today since it was the final day in the challenge! I'm glad my persistence paid off today and for the 99 days before that.

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)
2. [IPERS Data PDF](https://www.ipers.org/sites/default/files/SAFR-2019%20final.pdf)
3. [Find object by id in an array of JavaScript objects](https://stackoverflow.com/questions/7364150/find-object-by-id-in-an-array-of-javascript-objects)
4. [Regex](https://stackoverflow.com/questions/721304/insert-commas-into-number-string)

### Day 99: February 3, 2020

**Today's Progress:** Part of my struggle today has been that everything seems to be bogged down and working slowly on CodePen with this project. I know I'm not running the most efficient code and I have a lot of `console.log`s, but it's all necessary stuff to try and debug this project. I'm still working on getting the color scale to work in a reasonable way, and the way I'm approaching this is to try and convert the amounts to Number types so that they can interpreted by the scale.

**Thoughts:** It's more of the lagginess than anything that's really getting to me today. 

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)
2. [IPERS Data PDF](https://www.ipers.org/sites/default/files/SAFR-2019%20final.pdf)

### Day 98: February 2, 2020

**Today's Progress:** I have a working tooltip now and now am trying to puzzle out how to make the colors work in a choropleth style. I'm starting off by trying to convert all of the amounts to `Number` types, which I think will be necessary, but my approach seems like it may not work.

**Thoughts:** Now that the whole getting-the-map-to-render portion is done, this project isn't quite as daunting, but I still have a ways to go.

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)
2. [IPERS Data PDF](https://www.ipers.org/sites/default/files/SAFR-2019%20final.pdf)

### Day 97: February 1, 2020

**Today's Progress:** I somehow got the projection and such to work! The rest of my time was finding the data and getting it in a format that I should be able to use for the project itself.

**Thoughts:** Very happy to have something displaying now! Data is very hard to clean up and get formatted. I was told to learn vim macros when I was expressing this to a friend of mine, haha.

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)
2. [IPERS Data PDF](https://www.ipers.org/sites/default/files/SAFR-2019%20final.pdf)

### Day 96: January 31, 2020

**Today's Progress:** Still not getting anything to work. I'm trying to research other projects to see what they're using and figure out if I need a projection and all the bells and whistles that go with using that.

**Thoughts:** It's interesting that the fCC project doesn't require the use of projections at all especially when they're a major component of almost every other project I look at. It makes for a difficult time when working on your own map that (potentially) needs a projection.

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)

### Day 95: January 30, 2020

**Today's Progress:** I continued working on my choropleth map, only to find out that it's not so easy when your data doesn't match what you learned in past projects. I'm trying a lot of things to try and get something to display, but I'm not having any luck. 

**Thoughts:** I'm pretty used to struggling against TopoJSON and such by now, but it doesn't make it less frustrating, haha.

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)

### Day 94: January 29, 2020

**Today's Progress:** I finished Managing Packages with Npm yesterday, and got about halfway through the Basic Node and Express challenges. I also started work on a personal project, which will be a choropleth map similar to the one created earlier for the fCC challenge. 

**Thoughts:** Using Glitch has been an interesting experience so far. It looks like a pretty versatile platform for making web apps. Server-side code pretty new territory for me.

**Link(s) to work:**
1. [Managing Packages with Npm](https://www.freecodecamp.org/learn/apis-and-microservices/managing-packages-with-npm/)
2. [Basic Node and Express](https://www.freecodecamp.org/learn/apis-and-microservices/basic-node-and-express/)
3. [New Choropleth Map (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)

### Day 93: January 28, 2020

**Today's Progress:** Finished the treemap! I really didn't need to do much to get the text for the legend to appear right. I had to rearrange the logic of my items and change how some data flowed through the legend components, but once that was figured out, I had pretty smooth sailing. I fixed the colors so that they don't repeat in the scale by using an interpolator. After that it was just centering the visualization and adding the appropriate text and ids needed for the tests to pass.

**Thoughts:** I didn't expect to finish this project so soon, but I'm glad to finish it. My heart is torn between starting my own projects and progressing in fCC with the API challenges since I really want to start learning server-side code. I'll probably dabble into the challenges after I commit this but work on personal projects for the last week (!) of this challenge.

**Link(s) to work:**
1. [Treemap Diagram](https://codepen.io/legendoflilac/pen/xxbQpWE)

### Day 92: January 27, 2020

**Today's Progress:** Learned that part of my issue with the label was that I needed to put the `rect`s in a container, namely a `g` element, since rectangle elements are not containers, so adding a text element to them will be ignored. Now I'm trying to get the rect elements inside of the g elements so they display correctly.

**Thoughts:** Legends are such a problem point for me! I really have a hard time with them.

**Link(s) to work:**
1. [Treemap Diagram (WIP)](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [Treemap Example](https://codepen.io/freeCodeCamp/pen/KaNGNR)
3. [Treemap Example by HIC](https://codepen.io/HIC/pen/bxzpRR)
4. [Treemap Example by Carl Childers](https://codepen.io/carlchil/pen/QZvwvN)
5. [d3 Node Labeling](https://stackoverflow.com/questions/11102795/d3-node-labeling)

### Day 91: January 26, 2020

**Today's Progress:** Almost exclusively been working on the legend today since I want to make it different from the example and have more horizontal action going as opposed to the 3-column vertical legends I've been seeing. Unfortunately, I don't know much about how to create legends in this way, so it's been a day of experimenting and still not quite getting where I need to be. 

**Thoughts:** Hopefully within the next few days I'll get the legend working! It's quite difficult to manage and I've written down some of how the math *should* work, but it's still sort of a mystery, haha. 

**Link(s) to work:**
1. [Treemap Diagram (WIP)](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [Treemap Example](https://codepen.io/freeCodeCamp/pen/KaNGNR)
3. [Treemap Example by HIC](https://codepen.io/HIC/pen/bxzpRR)
4. [Treemap Example by Carl Childers](https://codepen.io/carlchil/pen/QZvwvN)

### Day 90: January 25, 2020

**Today's Progress:** I have text displaying now! Plus everything else is displaying correctly--I really need to be more aware of what I write sometimes, haha. I still had to reference some code eventually for some of the formatting, but I messed with the regex some since I didn't like how it would break FIFA into two lines. I also started work on the legend but I'm not super sure how I want it to look--most examples I've seen so far just look the same and I want to do something different. 

**Thoughts:** Looking forward to hopefully having a solid hour to work tomorrow instead of having time broken up across the day.

**Link(s) to work:**
1. [Treemap Diagram (WIP)](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [Treemap Example](https://codepen.io/freeCodeCamp/pen/KaNGNR)
3. [Treemap Example by HIC](https://codepen.io/HIC/pen/bxzpRR)

### Day 89: January 24, 2020

**Today's Progress:** I played with getting the text to display, but I don't want to copy and paste someone else's work and want to work through it on my own. I'm also struggling with getting the `<g>` elements to render right, since there are general elements on top of/with the `<rect>` elements to aid with the tooltip, which is coincidentally also not working. 

**Thoughts:** I don't want to have to look so heavily to the examples/other people's projects, but I'm at a loss for what to do in order to get things to display in the necessary ways. It's frustrating. 

**Link(s) to work:**
1. [Treemap Diagram (WIP)](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [Treemap Example](https://codepen.io/freeCodeCamp/pen/KaNGNR)
3. [Treemap Example by HIC](https://codepen.io/HIC/pen/bxzpRR)
4. [How to get d3 treemap cell text to wrap and not overflow other cells](https://stackoverflow.com/questions/56623476/how-to-get-d3-treemap-cell-text-to-wrap-and-not-overflow-other-cells)

### Day 88: January 23, 2020

**Today's Progress:** So the reason why nothing displayed was because I forgot to add a `.enter()` after my data... Not sure if I'll live that one down for a bit, haha. So now I have a pretty arrangement of rectangles on the screen, and my next step is to add the text to it.

**Thoughts:** I'm upset how long it took for me to realize that small but important element was missing. Well, things move on, I suppose! 

**Link(s) to work:**
1. [Treemap Diagram (WIP)](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [Treemap Example](https://codepen.io/freeCodeCamp/pen/KaNGNR)
3. [Treemap Example by HIC](https://codepen.io/HIC/pen/bxzpRR)
4. [Enter/Exit](https://www.d3indepth.com/enterexit/)

### Day 87: January 22, 2020

**Today's Progress:** I added some elements to the program but nothing is displaying right now in the svg. I'll have to keep testing it to see what I need to add or change in order to make things work like they're supposed to.

**Thoughts:** It seems I always hit a day where nothing displays when I work on these projects. 

**Link(s) to work:**
1. [Treemap Diagram (WIP)](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [Treemap Example](https://codepen.io/freeCodeCamp/pen/KaNGNR)
3. [Treemap Example by HIC](https://codepen.io/HIC/pen/bxzpRR)

### Day 86: January 21, 2020

**Today's Progress:** I continued reading about implementing treemaps and learned that only `scaleOrdinal` and `scaleSequential` scales work with the d3 color scales that are built in. I'm going to use `scaleOrdinal` for my color scale this time to learn about how to generate colors that I don't have to explicity define. I also learned about the `sum` and `sort` methods for `d3.hierarchy`. Sort takes two children and then sorts them by a prescribed function--the one most useful for treemaps is `b.height - a.height || b.value - a.value` because it sorts the nodes by descending heights followed by descending values, giving the treemap its characteristic look.

**Thoughts:** I'm curious about implementing these features which are new to me, and I've been really hitting the D3 docs hard!

**Link(s) to work:**
1. [Treemap Diagram (WIP)](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [D3 API Reference - Hierarchy](https://github.com/d3/d3-hierarchy/blob/v1.1.9/README.md#hierarchy)

### Day 85: January 20, 2020

**Today's Progress:** I read about treemaps in the D3 documentation and from D3 Graph Gallery and got the initial code in to define some of the constants and load the JSON.

**Thoughts:** 

**Link(s) to work:**
1. [Treemap Diagram](https://codepen.io/legendoflilac/pen/xxbQpWE)
2. [D3 API Reference - Hierarchy](https://github.com/d3/d3-hierarchy/blob/v1.1.9/README.md#hierarchy)
3. [Observable D3 Treemap](https://observablehq.com/@d3/treemap)
4. [D3 Graph Gallery Treemap](https://www.d3-graph-gallery.com/graph/treemap_custom.html)

### Day 84: January 19, 2020

**Today's Progress:** Finished the project and passed the tests! I referenced the example project for help with the legend, which was really the last part I needed to finish with the whole thing. Then I went back and looked at some of the code I didn't understand as much. I chose a light mint color to put as the background for this project since the map is populated with gray tones. 

**Thoughts:** The lack of guidance on this project was intimidating at first, but after looking at enough examples I learned how to work with what little information I was given. I don't think maps will be my choice of data visualization projects in the future, but at least I have a few fundamentals down if I ever try to approach one again. After all, a dataviz on where the most banned/challenged books come from in America could be quite interesting...

**Link(s) to work:**
1. [Choropleth Map](https://codepen.io/legendoflilac/pen/VwYdLOp)
2. [Choropleth Map Example](https://codepen.io/freeCodeCamp/pen/EZKqza)

### Day 83: January 18, 2020

**Today's Progress:** I got the scale to work better (it was passing the wrong value to `colorScale()`) and changed the color scheme to grayscale. I referenced the example pen to find out how to get the map data and education data to interact and finally got it to work.

**Thoughts:** I was really stumped on how to make the map data and education data interact. Using `filter()` to find the object needed in the education data was really helpful.

**Link(s) to work:**
1. [Choropleth Map (WIP)](https://codepen.io/legendoflilac/pen/VwYdLOp)
2. [Choropleth Map Example](https://codepen.io/freeCodeCamp/pen/EZKqza)

### Day 82: January 17, 2020

**Today's Progress:** I tried playing with the scales again, but most of the map is still very purple. I added the tooltip so I could see how much the counties and the education information don't overlap. I'll need to find a way to make the id's of both data match up and return the information I need.

**Thoughts:** Got distracted somewhat, but I still made progress.

**Link(s) to work:**
1. [Choropleth Map (WIP)](https://codepen.io/legendoflilac/pen/VwYdLOp)

### Day 81: January 16, 2020

**Today's Progress:** I learned some about different scales, such as threshold and quantile scales, and attempted to apply them to the colors on the map. It's still a little off since everything is displaying the darkest color. I also got the state outlines to appear. 

**Thoughts:** Not a bad time today.

**Link(s) to work:**
1. [Choropleth Map (WIP)](https://codepen.io/legendoflilac/pen/VwYdLOp)
2. [Choropleth Reference for State Outlines](https://observablehq.com/@d3/choropleth)
3. [Quantile, Quantize, and Threshold Scales](https://observablehq.com/@d3/quantile-quantize-and-threshold-scales)

### Day 80: January 15, 2020

**Today's Progress:** I got the map to appear! Turns out we don't need to mess with projection for this project, which was throwing things off. Next is figuring out how to get the education data into a color scale and applying it to the fill color of the counties. I also want to figure out how to give the states a stroke if possible.

**Thoughts:** Sometimes the most progress happens in the morning when I'm not expecting much to happen!

**Link(s) to work:**
1. [Choropleth Map (WIP)](https://codepen.io/legendoflilac/pen/VwYdLOp)

### Day 79: January 14, 2020

**Today's Progress:** Still confused on how to actually get things to render right with the type of data given for the project and I've been reading a bit to see if more explanations are given. I also found a map that adjusted to the window size, which I might try and adapt eventually. I attempted to see if I could get something to load in CodePen, only to realize that the CDN links listed in the project description don't play nicely with CodePen, leaving me to have to find the link that did work. And now there's a big black box on my screen and I don't know what to do with it, haha.

**Thoughts:** While I appreciate having to dig for information to get this project to work, I think the transition to this could have been easier if users had been exposed to paths, using Topo/GeoJSON, or just making maps in general. Or, y'know, providing the right links to the data...

**Link(s) to work:**
1. [Responsive TopoJSON Sizing with d3.js](http://bl.ocks.org/jczaplew/4444770)
2. [TopoJson](https://github.com/topojson/topojson)

### Day 78: January 13, 2020

**Today's Progress:** I did another learning day, partly dabbling in greater topics like colors in data visualizations and partly focused on the choropleth project at hand. From reading some of Mike Bostock's work, I realized that a lot of thought has to go into a visualization, namely that the geometry has to match the data. If your population data is from one year, it makes sense to find census tracts or other topology from that same year. I learned some about the difference between TopoJSON and GeoJSON, learning in the process that one of the files given for the project is a TopoJSON file. I will need to consider this as I move forward with the project.

**Thoughts:** Diving deeper into these topics is actually helpful for gaining a foundational understanding that I need to start the project. I think if I had just tried to hash it out right away I would have been frustrated. 

**Link(s) to work:**
1. [Choropleth Map (WIP)](https://codepen.io/legendoflilac/pen/VwYdLOp)
2. [Let's Make a Map](https://bost.ocks.org/mike/map/)
3. [Command-Line Cartography](https://medium.com/@mbostock/command-line-cartography-part-1-897aa8f8ca2c)
4. [Butterfly effect: OECD's data visualisation fail leads to media panic](http://datawanderings.com/2017/02/23/oecd-data-visualisation/#more-2234)
5. [Colorful nonsense: what does your data visualisation actually say?](http://datawanderings.com/2017/11/26/colourful-nonsense-data-visualisation/#more-2416)

### Day 77: January 12, 2020

**Today's Progress:** I started learning about choropleth maps and how to start making one in D3. The pattern I've found for most of the projects is:
	- Assign width/height as normal
	- Assign projection, such as `d3.geoAlbersUsa()`, like we'll be using for this project
	- Assign path as `d3.geoPath().projection(projection)`
	- Initialize svg canvas
	- Load data through d3.json
	- Draw map using paths

Additionally, I learned about using templates in CodePen and dove the tiniest bit into Promises in Javascript in reference to how it can be used with creating maps in D3. 

**Thoughts:** It was good to have just a knowledge-gathering session instead of a hard coding/debugging session. I may have to do this on days I don't have as much time to focus on coding, which is every Monday for me currently. I don't want to skip a day since I have a goal date in mind for me to finish all 100 days. I'll have to learn more about paths in SVG as well.

**Link(s) to work:**
1. [Making a Map in D3.js v.5](http://datawanderings.com/2018/10/28/making-a-map-in-d3-js-v-5/)
2. [d3CompositeProjections using the new d3js v5](http://bl.ocks.org/rveciana/51cfe6249cf7de532000af68fb3b5183)
3. [d3-geo](https://github.com/d3/d3-geo/blob/v1.11.9/README.md#geoPath)

### Day 76: January 11, 2020

**Today's Progress:** Finished the heat map! I did some last adjustments on the color scale to make it more colorblind-friendly, I used an example pen to help learn how to make the legend (learning in the process that `d3.range()` has `start, stop`, and a very useful (and in this case necessary) `step` parameter. I cleaned up some of the code and added some comments in areas where I might forget something useful I learned while doing this. 

**Thoughts:** I kind of want a break from doing D3 things, but I'm not sure what I would do instead. I have interest in learning about promises in JS and asynchronous code in general, since I'm using it with these projects but my understanding is limited. I also read about server-side code yesterday, and while it was super neat, I was definitely overwhelmed. I'll link it here so I remember it.

**Link(s) to work:**
1. [CodePen -- Heat Map](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [Example CodePen used for reference on Heat Map](https://codepen.io/TungstenNo74/pen/WrMzJr)
3. [Color Palette](https://venngage.com/blog/color-blind-friendly-palette/)
4. [d3.range() function](https://www.geeksforgeeks.org/d3-js-d3-range-function/)
5. [Express/Node introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
6. [Setting up a Node development environment](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment)

### Day 75: January 10, 2020

**Today's Progress:** Now that we've largely moved on from tooltip woes, I'm onto figuring out how to create a legend that is useful for the variance data. I can display the three colors used to create the color scale just fine, it's just figuring how to populate some of the in-between colors to actually make the legend useful to a viewer.

**Thoughts:** I'm 75% of the way to the finish line of this 100 Days of Code experiment! 

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [Example CodePen used for reference on Heat Map](https://codepen.io/TungstenNo74/pen/WrMzJr)

### Day 74: January 9, 2020

**Today's Progress:** Today was tooltip adventures. I got the basics done, but the `div` kept displaying at the bottom and I was having a hard time figuring out why that was happening. Looking at my past pen, I saw the difference when inspecting the tooltip--I was accidentally appending a `<class>` instead of adding the attribute `class`. Another facepalm moment!

**Thoughts:** I'm feeling like I understand HTML-based tooltips more now after doing some research on them. 

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [StackOverflow D3 Positioning tooltip on SVG element](https://stackoverflow.com/questions/21153074/d3-positioning-tooltip-on-svg-element-not-working)
3. [StackOverflow D3 Position tooltips using element position, not mouse position](https://stackoverflow.com/questions/16256454/d3-js-position-tooltips-using-element-position-not-mouse-position)

### Day 73: January 8, 2020

**Today's Progress:** Part of my problem was that I forgot that I needed to scale some of my attributes, like the `x` and `y` ones on the rectangles, to fit the svg. :woman_facepalming: But now the data is displayed, and I played some with the padding of the bands and also got a color scale going so the fill color changes with the value of variance.

**Thoughts:** Big steps have been made this morning after two or so days of being blocked from meaningful progress. I knew I had to be missing fundamental for the bands to not display right, but when you're too close to your project and so intent on making progress instead of being present, it's hard to see what you're overlooking.

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 72: January 7, 2020

**Today's Progress:** So I think some of the data was rendering maybe, but it was too small to see? Regardless, we have something showing up now. It's just a matter of getting it to populate the screen appropriately, then getting the fill colors right, and a whole slew of other things...

**Thoughts:** Was definitely frustrated until I started playing some with the `.data` attribute and noticing a small blue cluster near the top of the chart, near where January was. This project has really tested my patience this far because I think I should be knowing how to do these things and little stuff like getting the data on the screen is tripping me up.

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 71: January 6, 2020

**Today's Progress:** Kept working on the scales. Not able to get data to render at all.

**Thoughts:** Unsure how to proceed. Still feeling too tired to effectively do work on this.

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 70: January 5, 2020

**Today's Progress:** Looked for help on using colors in D3. I tried creating a color scale and appending rectangles, but I didn't get anything to display yet. 

**Thoughts:** I'm tired from the day and not finding a good solution for my problems was discouraging. Hopefully my struggle today leads to a path to knowledge tomorrow. Or the next day.

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [CodePen -- An Example Heat Map from Christian Wimber](https://codepen.io/TungstenNo74/pen/WrMzJr)


### Day 69: January 4, 2020

**Today's Progress:** Well, I went from the problem of only having one tick to having way too many ticks in the axis. This was solved thanks to `tickValues()` and StackOverflow. But really, the solution was to set `tickValues()` so that it filters the xScale's domain to only return one in every 10 (or whatever interval you like). I also got the y-axis set up, which was much easier since I had the x-axis to go off of. I also wrote one for the color scale, but I'm not sure if it's the right approach. The next challenge will be adding the cells and making sure the right cells get the right colors.

**Thoughts:** It's a relief to know that D3 can be flexible sometimes, even if sometimes it's a little silly in other ways. I'm really liking using `margin` as an object and being able to adjust margin values whenever I need to as opposed to having magic numbers that I have to search for and pray they change the thing I want it to. I did it on the last project too, but I didn't really appreciate it until this one.

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [StackOverflow -- Reduce number of ticks with filter()](https://stackoverflow.com/questions/40199108/d3-v4-scaleband-ticks)

### Day 68: January 3, 2020

**Today's Progress:** Thus begins another session with fighting with the x-axis! At first I wasn't getting anything to display right because I accidentally forgot to put `[]` around my range, and now I've got the problem of the data not being split into individual bands, instead forming one large tick with all the years I need... 

**Thoughts:** Maybe someday I'll have some luck with getting axes set up right.

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 67: January 2, 2020

**Today's Progress:** Started the heat map. I started thinking about ways to make it responsive, but I think I may need to just make the visualization first since I don't know much about constructing a heat map yet. There might be some different scales involved since there's a range of colors used in the example, and I don't know much about that yet.

**Thoughts:** Excited to be starting a new project!

**Link(s) to work:**
1. [CodePen -- Heat Map (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [Example of Heat Map](https://www.d3-graph-gallery.com/graph/heatmap_tooltip.html)


### Day 66: January 1, 2020

**Today's Progress:** Got the tests to pass! My issue was that in my mouseover function for the tooltip I passed the callbacks of `(d,i)` already, and when I was setting the attribute of `data-year`, I was passing them again, which was unnecessary. I added a little flex box to make it like my first project and started looking into how to make a responsive D3 project. I don't think this project is going to work well with it without digging myself into a deep hole, but I'm going to keep it in mind for my next few projects. Data visualizations need to work with small screens too!

**Thoughts:** Having success with the scatter plot was a good way to start the year!

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [A simple way to make D3.js charts responsive](https://medium.com/@louisemoxy/a-simple-way-to-make-d3-js-charts-svgs-responsive-7afb04bc2e4b)
3. [Responsive D3.js](https://brendansudol.com/writing/responsive-d3)
4. [viewBox attribute with svg height and width attributes set](https://stackoverflow.com/questions/44322617/viewbox-attribute-with-svg-height-and-width-attributes-set)

### Day 65: December 31, 2019

**Today's Progress:** Still working on getting the legend to be right. Ran through the tests, but it seems that #15 isn't working the way it should for some reason. So I'll have to troubleshoot that and then work on the design of the project.

**Thoughts:** Last day of the year! This legend has been giving me trouble and now the tests aren't all right, but I've had a lot more fun figuring out how D3 works with this project. I'm thinking I would like to set up a local environment where I can develop the visualizations without solely working on it with CodePen.

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 64: December 30, 2019

**Today's Progress:** More playing around to get the legend to work.

**Thoughts:** Aaaaaaaaaah. Everything is much harder to work with while ill.

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [CodePen -- Heat Map by GiaFil -- Referenced for use of legend](https://codepen.io/GiaFil/pen/Edbeyq)

### Day 63: December 29, 2019

**Today's Progress:** I added the id's needed for the testing suite and I started working on the legend.

**Thoughts:** Not much to think about, just trying to set everything up for the tests.

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 62: December 28, 2019

**Today's Progress:** I created a way to make the dots have different fill colors depending on whether there was doping data available. I also added the tooltip for more information about the plotted point.

**Thoughts:** It's coming along smoothly. I didn't remember how to make the tooltip work, so I had to look back on my bar chart project to see what I used for that. I was stumped for a bit on how to make the color-changing aspect work, but the solution wasn't has hard as I thought.

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 61: December 27, 2019

**Today's Progress:** I fixed my previous code to make better use of the `.timeFormat()` and `.timeParse()` options, which has helped simplify how the years and times are evaluated. And now I have dots on the plot!

**Thoughts:** I'm happy to finally have dots! It was a bit of a struggle, but sometimes, you just need to take a break or actually think about what your code is doing instead of what you're intending it to do.

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 60: December 26, 2019

**Today's Progress:** I finally fixed what was wrong with the y axis! I also learned that D3 has a method to parse dates without calling a `Date()` object and modifiying it. It took a lot of research to figure out why `.timeFormat` kept throwing an error at me, but now it's ready to have data plotted!

**Thoughts:** Sadly haven't been able to do this every day this week with the holidays and busy work schedules, but the goal is to not miss two days in a row and so far that's been manageable. 

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)
2. [StackOverflow -- tickFormat usage](https://stackoverflow.com/questions/18474620/d3-js-tickformat-adding-a-sign-without-multiplying-by-100)
3. [StackOverflow -- tickFormat not working](https://stackoverflow.com/questions/42485211/d3-tickformat-not-working)
4. [JSFiddle -- Doping Bicyclists Data](https://jsfiddle.net/swxbx0Lt/)

### Day 59: December 24, 2019

**Today's Progress:** Continued scatter plot, attempting to format the y axis properly. I need to find a way to explicitly define the formatting of the times so that they display on the graph properly in MM:SS format.

**Thoughts:** More playing with date objects, woo!

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)


### Day 58: December 22, 2019

**Today's Progress:** I started the scatter plot project.

**Thoughts:** I now remember how much I didn't like Date objects when working with the last project, since Dates are back again! I did a better job this time around just setting up the underlying foundation for the visualization since I had experience struggling with the bar chart.

**Link(s) to work:**
1. [CodePen -- Scatter Plot (WIP)](https://codepen.io/legendoflilac/pen/mdymwoz)

### Day 57: December 20, 2019

**Today's Progress:** I managed to get the full graph to show and adjusted it so it displays the data like in the example project. I worked on creating the tooltip, which was trickier than I thought. I'm going to do some style adjustments next. *Update*: Submitted the project with all tests passing.

**Thoughts:** I'm definitely feeling the impostor syndrome today. It's somewhat justified since I can't seem to really make progress on this project without turning somewhere for help. Not that help is a bad thing, I just have an expectation of myself to be better and I'm failing to meet that. 

**Link(s) to work:**
1. [CodePen -- Bar Chart (WIP)](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)
2. [How to create tooltips in D3.js](https://www.competa.com/blog/how-create-tooltips-in-d3-js/)


### Day 56: December 19, 2019

**Today's Progress:** Well, one of my problems with bar width was fixed when I noticed that the CSS class assigned to the bars was affecting it! Still not out of the woods yet since I need to figure out the height issue.

**Thoughts:** Definitely wishing I had an outsider's perspective. It's hard going it alone and realizing past-you was a little dumb.

**Link(s) to work:**
1. [CodePen -- Bar Chart (WIP)](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)

### Day 55: December 18, 2019

**Today's Progress:** I tried working more with the data today. It gives the vague appearance of displaying the GDP over time, but the bars themselves don't reach the x axis.

**Thoughts:** I wish I had someone who could help me out with this. I feel like it should be a pretty easy solution, I'm just not seeing it with my limited perspective. All the bars seem to have the same width and height, they're just bunched close together and not forming long, skinny bars like I've seen in other examples of this project. 

**Link(s) to work:**
1. [CodePen -- Bar Chart (WIP)](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)

### Day 54: December 17, 2019

**Today's Progress:** I played more with the bar chart itself to understand how `transform` can modify the visibility of the axes, and I started digging into why the data refuse to display in a reasonable, bar-chart-like manner.

**Thoughts:** I could tell I was procrastinating this today since I didn't come home and engage right away. Since I did that, I was tired and couldn't focus well on the task, but adopting a less focused mindset helped me be calm and playful about the project a little more. 

**Link(s) to work:**
1. [CodePen -- Bar Chart (WIP)](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)
2. [Tutorials Teacher](https://www.tutorialsteacher.com/d3js/create-bar-chart-using-d3js)

### Day 53: December 16, 2019

**Today's Progress:** Working backwards today. After experiencing frustration with the current project, I'm going through tutorials and trying to gain a greater understanding of the fundamentals.

**Thoughts:** I think there's just too many pieces I'm trying to get to work at once, and it's not letting me make real progress. As a result, I'm consulting other resources and playing with examples in a temporary pen. It's a little frustrating, but I know this is just a part of learning.

**Link(s) to work:**
1. [CodePen -- Bar Chart (WIP)](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)
2. [Tutorials Teacher](https://www.tutorialsteacher.com/d3js/create-bar-chart-using-d3js)

### Day 52: December 15, 2019

**Today's Progress:** The axes are (mostly) fixed now. I'm working how to get the bars to display right.

**Thoughts:** It doesn't take much to make an hour pass doing this! It's interesting to play with different aspects and see how it changes things on the screen, but I still feel like I'm missing some fundamental concepts partly because I'm working with a newer version of D3 and partly because I'm just not familiar working with it in general.

**Link(s) to work:**
1. [CodePen -- Bar Chart (WIP)](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)

### Day 51: December 14, 2019

**Today's Progress:** The axes are giving me problems. I figured out how to get some of the promise stuff to work with D3, but I still have to map those values to the domain somehow and get the axes right. 

**Thoughts:** Well, the major obstacle for today has been figured out somewhat, but now I'm left messing with axes even before I start building the individual bars. I'm definitely not used to working with D3 yet. I know it can do some interesting stuff, but it's by no means beginner-friendly.

**Link(s) to work:**
1. [CodePen -- Bar Chart (WIP)](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)

### Day 50: December 13, 2019

**Today's Progress:** I started playing around with the bar chart challenge. 

**Thoughts:** I'm consulting other tutorials and sources for help with some of this. While I can appreciate the basic intro that fCC gives for this, the concepts covered don't translate the best over to an actual project. Regardless, I still think this will still be pretty cool when I'm done.

**Link(s) to work:**
1. [CodePen -- Bar Chart](https://codepen.io/legendoflilac/pen/QWwKjoa?editors=0011)

### Day 49: December 12, 2019

**Today's Progress:** Finished the short API and AJAX section.

**Thoughts:** I wasn't the most focused on this section. Most fCC stuff guides you a bit more piecemeal through concepts rather than throwing a code block at you and saying "hey, copy and paste this into the editor to complete the challenge." I also find it curious that the D3 section failed to mention `d3.json()`.

**Link(s) to work:**
1. [freeCodeCamp -- Data Visualization -- All of the JSON APIs and AJAX Challenges](https://www.freecodecamp.org/learn/data-visualization/json-apis-and-ajax/)

### Day 48: December 10, 2019

**Today's Progress:** Finished the D3 section. 

**Thoughts:** I had a little trouble following the later parts of this section, but it was mainly due to my lack of focus due to real life events.

**Link(s) to work:**
1. [freeCodeCamp -- Data Visualization -- Change the Color of an SVG Element](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/change-the-color-of-an-svg-element/) through [freeCodeCamp -- Data Visualization -- Add Axes to a Visualization](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/add-axes-to-a-visualization)

### Day 47: December 9, 2019

**Today's Progress:** Started learning about data visualization with D3. I learned about selecting HTML elements, adding attributes and styles, and played with SVG graphics. Because of how SVG works, it will invert the traditional bar chart, but there's a method to make the bar chart appear as we normally see it day-to-day.

**Thoughts:** I like what I'm learning so far, and it's super cool to be using a library used by one of my favorite data-driven journalism websites, [The Pudding](https://pudding.cool/).

**Link(s) to work:**
1. [freeCodeCamp -- Data Visualization -- Add Document Elements with D3](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/add-document-elements-with-d3) through [freeCodeCamp -- Data Visualization -- Invert SVG Elements](https://www.freecodecamp.org/learn/data-visualization/data-visualization-with-d3/invert-svg-elements)

### Day 46: December 8, 2019

**Today's Progress:** Holy cow things actually fell into place today and I'm at 29/29 tests passed. Instead of updating immediately when `runningTimer` hit 0, I changed it so that the timer went from session to break at -1 instead, giving the interval a chance to update the display. I also mislabeled an id name, which messed up some of the tests initially. 

**Thoughts:** I think this is a neat project, but I just want to throw it at a wall after all the silly errors I encountered! I'm very impressed how I handled this project and built it through learning first how to do a countdown, then how to make a countdown that has a reset button, then one that can pause... all adding up to the point where it has the full functionality of a pomodoro timer. I didn't style it much, but that can happen later. Having the main logic working is the most important part. And with that, I'm moving on to the second part of my 100 Days of Code/Winter of Code challenge--data visualization! This is another part of the freeCodeCamp curriculum, and it's one I've been looking forward to doing for a long time.

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 45: December 7, 2019

**Today's Progress:** Still working on the issue of not reaching 00:00.

**Thoughts:** 

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 44: December 6, 2019

**Today's Progress:** Pausing works again with the new approach. I worked on various aspects of the program today and started testing. My timer doesn't reach 00:00 however, and it throws me an interesting error in the test suite. The error message doesn't give me much to go off of, but I know lots of people have struggled with their timers not hitting/displaying 00:00. 

**Thoughts:** Not many thoughts, today, just an amount of work.

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 43: December 5, 2019

**Today's Progress:** I got the session and break lengths to increment and decrement without much trouble, and I have a place in state for a `runningTimer` which tracks the progress of the timer that is running. Unfortunately, how it's currently set up means that the play/pause button doesn't work again because `runningTimer` will reset when `startCountdown()` is called again. 

**Thoughts:** Sometimes it's amazing how much I can get done at the beginning of a session and then struggle really hard to get things to work for the rest of the hour. Progress is not linear!

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 42: December 4, 2019

**Today's Progress:** I'm trying to figure out how to increment and decrement the `sessionLength` and `breakLength` without having to copy/paste and change values. I also need to find a way to take this state and essentially copy it to the running timer so that `sessionLength` and `breakLength` aren't directly modified. When they are modified, the next time it becomes a work session or a break session, the timer won't reset back to the original values and instead continue to count downward from zero, which is not how this timer is supposed to function.

**Thoughts:** There's a part of me that wants to start cleaning up my code already, but I know I need to just get the program working first before I do any drastic refactoring.

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 41: December 3, 2019

**Today's Progress:** I worked on the session-flipper and can get the timer to switch between session and break, but it seems that when break flips back to session, it starts counting down and not resetting to whatever the first session number was, which is a problem. I may have to store the original number in session/break and use that to reset that part each time.

**Thoughts:** I don't find myself as excited about this project, but when I start working on it, I can't seem to find a good place to stop and end up going over my allotted hour because I tell myself I want to fix one more issue, add one more thing... it's the old adage that motivation comes from action, not out of desire to do something.

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 40: December 2, 2019

**Today's Progress:** Today didn't consist of much. I'm puzzling through how to make the timer switch between the session period and the break period.

**Thoughts:** I feel like I just keep adding a bunch of parts to state. Uncertain if that's okay to do in a larger sense, but what do I know? This is the first app that's really required its use.

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 39: December 1, 2019

**Today's Progress:** I worked on disabling the start button after clicking the Start Countdown button so that multiple `setInterval()`s wouldn't occur. I also added a reset button that sets the session back to my original state. Eventually I will need to get the countdown to trigger the buzzer and switch to the resting countdown. 

Additionally, [Advent of Code](https://adventofcode.com/) starts today! I just learned about it yesterday and decided to try it, though I doubt I'll be able to do it every day. I solved the first two challenges with Python. It's been a while since I've used Python, and one big takeaway was that `for line in file_object:` will set the iterator to the first line, but `file_object.readline()` will move the iterator *again*, which caused the first line in my input file to be skipped.

**Thoughts:** The timer is going slowly but without major issues in understanding (so far), but pseudo-physics problems are way more fun!

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 38: November 30, 2019

**Today's Progress:** I have no idea how to work with `setInterval()` and have even less clue about how to structure this project. I started learning about how to use `setInterval()` and am playing with it in the CodePen app.

**Thoughts:** It seems this is going to need even more thought and planning on how to use components/functions compared to the calculator app. At least I'm now used to being overwhelmed by all the unknowns. 

**Link(s) to work:**
1. [CodePen -- Pomodoro Timer (WIP)](https://codepen.io/legendoflilac/pen/PowYRvZ)

### Day 37: November 29, 2019

**Today's Progress:** I finished the `eval()` calculator! There's still some bugs with the program, but I passed the main tests! For example, the decimal won't display until after you input something else, and I don't have a limit to the amount of digits to enter, so the display could get very large. It needs some CSS tweaks and some optimization as well, and I would like to get the RPN version to work eventually too.

**Thoughts:** It was a very happy moment to see that 16/16 tests passed! Now on to the Pomodoro timer!

**Link(s) to work:**
1. [CodePen -- Calculator w/eval()](https://codepen.io/legendoflilac/pen/abbMvjm)


### Day 36: November 27, 2019

**Today's Progress:** I tried another method for multiple operators, but it ended up causing more problems than it solved. I reverted back to the last algorithm I used for it to see if I can tweak it in a way that will allow it to work as intended.

**Thoughts:** It was another day where I got my hopes up for things to work, but was let down. At least now I know that one approach for sure doesn't work.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)
2. [CodePen -- Calculator w/eval() (WIP)](https://codepen.io/legendoflilac/pen/abbMvjm)

### Day 35: November 26, 2019

**Today's Progress:** I attempted working on the multiple operator inputs test again, but I'm still not able to figure out a good way to do it.

**Thoughts:** I am frustrated with working on this issue. No good way to talk around my thoughts on this, make it seem like I'm not frustrated. My solutions so far have managed to, under some cases, mutate `numArray` wrong, which leads to an incorrect result. I felt like I was almost there, but today was a two steps forward, two steps back sort of day.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)
2. [CodePen -- Calculator w/eval() (WIP)](https://codepen.io/legendoflilac/pen/abbMvjm)

### Day 34: November 25, 2019

**Today's Progress:** I fixed an evaluation issue and started working on a way to handle multiple operator inputs.

**Thoughts:** It's been rough but I'm trying to make it work.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)
2. [CodePen -- Calculator w/eval() (WIP)](https://codepen.io/legendoflilac/pen/abbMvjm)

### Day 33: November 24, 2019

**Today's Progress:** I'm passing 14/16 tests now. I'm having issues with handling the mistaken double operator (someone pressing +/ should ignore the plus and continue operating with the division), evaluating a decimal with precision (something returns oddly on the test that is run), and the negative number ordeal (the test 5*-5 will return 25).  

**Thoughts:** I'm happy that I'm now passing most of the tests! The last two might be a struggle, but persistence is key.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)
2. [CodePen -- Calculator w/eval() (WIP)](https://codepen.io/legendoflilac/pen/abbMvjm)

### Day 32: November 23, 2019

**Today's Progress:** Yesterday I *think* I figured out the shunting-yard algorithm to the point I need it to be in order to give a correct RPN notation. Today I continued work on the `eval()` version, specifically addressing multiple zeroes and decimals. I also am working on figuring out what to declare a "current" input by the user--having this helps with evaluating the multiple zeroes and decimals and it might be what I need to do in order to progress, even though it's an amount of refactoring. 

**Thoughts:** I've worked on this for over a week now, but I'm not going to let it get me down! I'm starting to think about how to solve some of these problems during work, which is neat.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)
2. [CodePen -- Calculator w/eval() (WIP)](https://codepen.io/legendoflilac/pen/abbMvjm)


### Day 31: November 22, 2019

**Today's Progress:** Did some more work on the manual evaluation. More issues came up, so I switched to the other fork with the `eval()` method for the time being until I can fix the algorithms to do the manual evaluation.

**Thoughts:** I understand why `eval()` can be dangerous, especially when it comes to parsing user input, but it's unfortunately convenient for this project and simplified things which have plagued me for days. Now I've got to find ways to handle misinputs, especially concerning the test cases of multiple zeroes before a number and too many decimals. 

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)
2. [CodePen -- Calculator w/eval() (WIP)](https://codepen.io/legendoflilac/pen/abbMvjm)

### Day 30: November 21, 2019

**Today's Progress:** Working on more bugs in the RPN creator and evaluator. I'm fairly certain I solved an issue where a certain operator would add itself twice to the result, which was causing an amount of problems. I was very happy when my test input `5*5+1` evaluated to `26`. 

**Thoughts:** Well, I haven't given up on my manual method of calculation yet. I'm trying to stick it out and do it the hard way and then see how easy or hard the other way is to implement. Additionally I've been looking at some neat options for doing free courses online which deal with everything from discrete math to algorithms to data structures. My main focus is still on finishing these front-end projects and then diving deep into D3 and data visualization next, but these courses would be great to fold in at some point.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 29: November 20, 2019

**Today's Progress:** Working on the bugs in the RPN evaluator.

**Thoughts:** I'm getting discouraged with this project and might just make a version that uses `eval()` and come back to the RPN version later. Part of the reason is that I know the next project will take just as long, if not longer. But then again, I shouldn't worry so much about how long something takes as much as what I'm learning from it. 

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 28: November 19, 2019

**Today's Progress:** Debugging the evaluation parts of the app. Still plenty more to do yet!

**Thoughts:** Thank goodness for [JavaScript Tutor](http://www.pythontutor.com/javascript.html#mode=edit) for helping out with some of the reference errors I was having.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 27: November 18, 2019

**Today's Progress:** I'm mainly working on bug-squashing for the handleEvaluation function. One bug I had was that a specific condition in the if statement caused the whole app to not render, which was concerning. While I don't understand why it broke the way it did, isolating and fixing one of my regexes helped. Of course now I'm actually trying to get the program to calculate something, and my regexes are failing me again. 

**Thoughts:** Sometimes regexes are great, sometimes they're program-killers. 

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 26: November 17, 2019

**Today's Progress:** Worked more on conversion to RPN, attempted to figure out how to calculate from it. I may need to rework my solution in the future because I'm repeating myself a fair amount when I'm coding. 

**Thoughts:** This is taking longer than I would like, but I'm actually enjoying the process of figuring this problem out compared to the other projects. I never knew a calculator could be so complex!

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 25: November 16, 2019

**Today's Progress:** Added some code for handling operators, looked into the algorithm some more.

**Thoughts:** Whether I put in an official hour or not is hazy since I had a day jam-packed with things to do, but I did make some improvements to the code so I count that as a success!

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 24: November 15, 2019

**Today's Progress:** Watched a video on the shunting-yard algorithm and started writing a crude version of it. I also got operators to display along with my numbers. 

**Thoughts:** I'm excited about putting this algorithm to use now! It seems challenging from the outside (and I still might have some challenges putting it all together in the end), but it's actually fun to learn about.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 23: November 14, 2019

**Today's Progress:** Got some numbers to display. I continued looking into the shunting-yard algorithm and reverse Polish notation. Not entirely sure I understand how they work, but they seem key to understanding how to do this project without `eval()`. 

**Thoughts:** I remembered how to update the display from the fCC challenges, so I was happy I could implement that part easily. I otherwise feel like I'm moving at a glacial pace with this project compared to the others I've done. 

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

2. [Reverse Polish Notation](https://en.wikipedia.org/wiki/Reverse_Polish_notation)

3. [Shunting-Yard Algorithm](https://en.wikipedia.org/wiki/Shunting-yard_algorithm)

### Day 22: November 13, 2019

**Today's Progress:** Rendered some buttons and started working on event handler functions. I learned that using `eval()` is not widely supported by the JS community, but that it could be used in this project by sanitizing the input. It becomes more dangerous to use when it's using user input, but I'll see if I can work around using it anyway. I also did some cursory research into algorithms used by calculators.

**Thoughts:** Still overwhelmed. I find myself wanting to dig into more research instead of actually working on the code itself. Research has its value, but it shouldn't overshadow the whole hour I get per day to code. 

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 21: November 12, 2019

**Today's Progress:** Looked at Calculator Project, started contemplating how to approach this. 

**Thoughts:** As expected this project feels more overwhelming than the others. I need to take it piece by piece and not concern myself with making it completely functional right away.

**Link(s) to work:**
1. [CodePen -- Calculator (WIP)](https://codepen.io/legendoflilac/pen/ZEEMrde)

### Day 20: November 11, 2019

**Today's Progress:** After some lengthy debugging, I managed to finish it and pass all the tests! I had to use `.keyCode` instead of `.key` for one of the tests, which I only found out after some intense digging through the fCC forums. Even though `.keyCode` should be deprecated according to MDN, sometimes you have to work within what the tests detect. For the other test, I had to re-read and understand User Story #3 and ask myself if I was really fulfilling this criterion in order to find out why User Story #4 wasn't passing. Once I fixed those `id`s, I got 8/8 tests passed!

**Thoughts:** It took a long time to find those two relatively minor bugs, but I'm feeling accomplished (if a bit tired) overall. I'm a bit anxious about the next project, which is a calculator, since that will have a lot more moving pieces.

**Link(s) to work:**
1. [CodePen -- Drum Machine](https://codepen.io/legendoflilac/pen/gOOeENK)


### Day 19: November 10, 2019

**Today's Progress:** Got the display and sound to work! Also did some basic design work with CSS Grid.

**Thoughts:** Made a few leaps in progress today thanks to some trial and error and explanations of how to get audio to play. I'm nearly done with the project, but there's a few tests that I failed when I ran the fCC test suite. Tomorrow I'll have to see how to fix those issues.

**Link(s) to work:**
1. [CodePen -- Drum Machine (WIP)](https://codepen.io/legendoflilac/pen/gOOeENK)


### Day 18: November 9, 2019

**Today's Progress:** Drum Machine project.

**Thoughts:** I got all the buttons to at least appear thanks to `.map`. I developed the event handler some, but audio is still not working yet. I also have the display area to finish up. This is taking longer than expected, but I also haven't had as many long blocks of time to dedicate to this.

**Link(s) to work:**
1. [CodePen -- Drum Machine (WIP)](https://codepen.io/legendoflilac/pen/gOOeENK)


### Day 17: November 8, 2019

**Today's Progress:** Drum Machine project.

**Thoughts:** I was really optimistic that I would understand this better today, but I'm pretty sure I confused myself even more. Still haven't gotten even one button to work yet. 

**Link(s) to work:**
1. [CodePen -- Drum Machine (WIP)](https://codepen.io/legendoflilac/pen/gOOeENK)


### Day 16: November 7, 2019

**Today's Progress:** Drum Machine project.

**Thoughts:** It's one of those days where I don't know what I'm doing. I don't even know where to start for handling the key presses and playing the audio. I've been looking at how other people completed the project for reference, but I don't want to use ideas that work but are incomprehensible to me. I need to be able to understand what's going on in the project. I started to work on just getting one button to work, so we'll see if I can complete that during tomorrow's coding time.

**Link(s) to work:**
1. [CodePen -- Drum Machine (WIP)](https://codepen.io/legendoflilac/pen/gOOeENK)

### Day 15: November 6, 2019

**Today's Progress:** Started drum machine project.

**Thoughts:** I have the larger idea of the app written in React, but due to some of the tests I need to pass this time I may have to break apart the code into smaller components. Additionally, I'm not super sure what to use for audio. I'm torn between using the same audio files as in the sample project and finding some other audio to use to make it more fun. I'm also not sure how to handle keydown events in React, so that's something I need to learn and implement.

**Link(s) to work:**
1. [CodePen -- Drum Machine (WIP)](https://codepen.io/legendoflilac/pen/gOOeENK)

### Day 14: November 5, 2019

**Today's Progress:** Finished (?) markdown previewer project.

**Thoughts:** I started to not be looking forward to this project because I was struggling so much getting the design to look how I envisioned it. I had to have a moment today where I just accepted it where it was, ran the tests on it, saw that they passed, and was just happy I did that much. There may come a period of time when I want to revise, but for right now, it's just going to look like this.

**Link(s) to work:**
1. [CodePen -- Markdown Previewer](https://codepen.io/legendoflilac/pen/GRRyBLz)

### Day 13: November 4, 2019

**Today's Progress:** Continued markdown previewer project, with a focus on CSS.

**Thoughts:** CSS seems completely foreign to me sometimes. What I intend and what happens on screen are very different things sometimes. I still have to look into breaking the app into components for practice, but I'm so focused on the design aspect that the React stuff is gone by the wayside in my mind.

**Link(s) to work:**
1. [CodePen -- Markdown Previewer (WIP)](https://codepen.io/legendoflilac/pen/GRRyBLz)

### Day 12: November 3, 2019

**Today's Progress:** Continued markdown previewer project.

**Thoughts:** I focused less on breaking up the app into different components and instead researched how to get marked.js to work in the intended manner. I learned that passing `{marked(this.state.input)}` displays the return value from marked, but in order to really preview how the markdown will look, it needs to be passed as HTML. This is accomplished with the `dangerouslySetInnerHTML` property in React. There were some other aspects of marked.js that needed to be changed in order to work in CodePen, namely the way links are handled. [This forum post](https://www.freecodecamp.org/forum/t/use-of-jquery-in-react/219850/13) helped explain some of that. 

**Link(s) to work:**
1. [CodePen -- Markdown Previewer (WIP)](https://codepen.io/legendoflilac/pen/GRRyBLz)


### Day 11: November 2, 2019

**Today's Progress:** Started markdown previewer.

**Thoughts:** Time to throw myself at another project! Today I played with React to see how it would go. After I got some items to render on-screen, I began to think about how to structure the app and what parts will be stateful and stateless. 

**Link(s) to work:**
1. [CodePen -- Markdown Previewer (WIP)](https://codepen.io/legendoflilac/pen/GRRyBLz)

### Day 10: November 1, 2019

**Today's Progress:** Completed the random quote machine project.

**Thoughts:** Today was a healthy mix of playing with CSS and trying various methods to get the quote to tweet out properly. Another issue was—you guessed it—a typo in the jQuery selector! I was happy that's all it was. I also learned a bit about URL encoding with `encodeURI()`, `preventDefault()` for getting the the Twitter stuff to work, and cool things one can do with Font Awesome. Finishing a project this soon is really cool since I'm 10% of the way to 100 days!

**Link(s) to work:**
1. [CodePen -- Random Quote Generator](https://codepen.io/legendoflilac/pen/xxxXOmy)

### Day 9: October 31, 2019

**Today's Progress:** Worked on the random quote machine project.

**Thoughts:** After researching and trying to pull together ideas to make the quote generator work, I now have part of the code working. I can generate the mock quotes when the page loads, but I haven't gotten it to generate a new quote when the "New Quote" button is pressed. One of my setbacks this time was that I didn't put parentheses around `document` in my `$(document).ready()` function... if I had seen that sooner, it would have saved me some time. Live and learn! (Happy Halloween!)

**Link(s) to work:**

1. [CodePen -- Random Quote Generator (WIP)](https://codepen.io/legendoflilac/pen/xxxXOmy)

### Day 8: October 30, 2019

**Today's Progress:** Looked at jQuery and laid the foundations for the random quote machine project.

**Thoughts:** I refreshed myself on jQuery since I think it will be key to understanding and working with this random quote project. I then worked on adding elements to the pen I'm building this in to pass some of the easier tests. The main difficulty will be building script that gets the author/text in place and generates a new quote. 

**Link(s) to work:**

1. [CodePen -- Random Quote Generator (WIP)](https://codepen.io/legendoflilac/pen/xxxXOmy)

2. [freeCodeCamp -- Front End Libraries -- jQuery](https://www.freecodecamp.org/learn/front-end-libraries/jquery/)

### Day 7: October 29, 2019

**Today's Progress:** Completed the rest of the React challenges, attempted Redux and React/Redux challenges with varying degress of success. 

**Thoughts:** Throwing another framework in the mix definitely made things hard today. Makes me wonder about how the front-end libraries projects are going to go, especially since I haven't looked at Bootstrap, SASS, and jQuery in a while... let alone remember how to interact with certain parts of HTML and CSS. This could be a real uphill battle for a bit, but I know consistent daily effort is key.

**Link(s) to work:**
1. [freeCodeCamp -- Front End Libraries -- React](https://www.freecodecamp.org/learn/front-end-libraries/react/)

2. [freeCodeCamp -- Front End Libraries -- Redux](https://www.freecodecamp.org/learn/front-end-libraries/redux/)

3. [freeCodeCamp -- Front End Libraries -- React and Redux](https://www.freecodecamp.org/learn/front-end-libraries/react-and-redux/)

### Day 6: October 28, 2019

**Today's Progress:** Tackled fCC's React challenges again, this time with much greater understanding. Tomorrow I will start with the challenge [Optimize Re-Renders with shouldComponentUpdatePassed](https://www.freecodecamp.org/learn/front-end-libraries/react/optimize-re-renders-with-shouldcomponentupdate). 

**Thoughts:** I felt more confident doing these challenges a second time. This helped cement more of the fundamentals and helped me understand why I'm writing the code, rather than just blindly following the prompts. 

**Link(s) to work:** 

1. [freeCodeCamp -- Front End Libraries -- React](https://www.freecodecamp.org/learn/front-end-libraries/react/)

### Day 5: October 27, 2019

**Today's Progress:** React Docs and the React Tic-Tac-Toe tutorial.

**Thoughts:** React is starting to feel a little more familiar, but creating components, knowing the flow of information from one component to another, and doing anything outside of the examples still feels like a stretch. I feel a lot like I did when I was doing the algorithm challenges back when I was just learning JavaScript--like I wasn't given the tools to solve the problems and yet am still somehow expected to come up with an elegant answer. There's got to be a balance between hand-holding and throwing the baby into the ocean, but I haven't found it yet.

**Link(s) to work:** 

1. [React Docs -- Composition vs Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)

2. [React Docs -- Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

3. [CodePen React -- Tic-Tac-Toe](https://codepen.io/legendoflilac/pen/xxxrXXP)

### Day 4: October 26, 2019

**Today's Progress:** More docs!

**Thoughts:** I gleaned more information about React and forked the Tic Tac Toe pen on CodePen so I can follow along with the tutorial tomorrow. 

**Link(s) to work:** 

1. [React Docs -- Handling Events](https://reactjs.org/docs/handling-events.html)

2. [React Docs -- Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)

3. [React Docs -- Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

4. [React Docs -- Forms](https://reactjs.org/docs/forms.html)

5. [React Docs -- Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

### Day 3: October 25, 2019

**Today's Progress:** Reading the docs!

**Thoughts:** No real coding done today, just a lot of reading docs and figuring out the basics of React again. I liked the structure of the React docs as well--it gave me some ideas about how to structure my own documentation/tutorials in the future. 

**Link(s) to work:** 

1. [React Docs -- Hello World](https://reactjs.org/docs/hello-world.html)

2. [React Docs -- Introducing JSX](https://reactjs.org/docs/introducing-jsx.html)

3. [React Docs -- Rendering Elements](https://reactjs.org/docs/rendering-elements.html)

4. [React Docs -- Components and Props](https://reactjs.org/docs/components-and-props.html)

5. [React Docs -- State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)


### Day 2: October 24, 2019

**Today's Progress:** Working through React exercises on freeCodeCamp.

**Thoughts:** Some parts made more sense today, some parts didn't. Tomorrow I'm going to read the React docs and go from there.

**Link(s) to work:** 

### Day 1: October 23, 2019

**Today's Progress:** Working through React exercises on freeCodeCamp.

**Thoughts:** I should have started over from the beginning since it had been at least a month since I last looked at React. I didn't understand much of what I was doing, but I have a better vision of where to go now.

**Link(s) to work:**

### Pre-Challenge: October 21, 2019

**Thoughts:** I want to do this to create a commitment to coding, to finally work on some projects that have been brewing in my head for a while, and to improve my coding ability. I plan to work with the freeCodeCamp curriculum, specifically the Front End Libraries and Data Visiualization portion. Plus, everyone's always doing Summer of Code, and I think Winter of Code deserves more love. 
