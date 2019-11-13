# 100 Days Of Code - Log

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
