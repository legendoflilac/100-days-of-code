# 100 Days Of Code - Log

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
