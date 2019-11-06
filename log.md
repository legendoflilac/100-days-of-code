# 100 Days Of Code - Log

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

**Thoughts:** Today was a healthy mix of playing with CSS and trying various methods to get the quote to tweet out properly. Another issue was—you guessed it—a typo in the jQuery selector! I was happy that's all it was. I also learned a bit about URL encoding with `encodeURI()`, `preventDefault
