# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **KASHAF MUJEEB**

Time spent: **10** hours spent in total

Link to project: [Link to the game] https://sponge-jade-quarter.glitch.me
[Link to the code for the game] https://glitch.com/edit/#!/sponge-jade-quarter

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:


https://media.giphy.com/media/kW6TL5t8DTfUG9aXTd/giphy.gif


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

  I used the following websites for this pre-work:
[StackOverflow] https://stackoverflow.com/questions/67559504/how-to-modify-a-particular-frequency-in-a-sound-file-in-p5-js
[w3w schools] https://www.w3schools.com/css//css_font_websafe.asp , https://www.w3schools.com/html/
[MDN Web] Docshttps://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Color_picker_tool
 
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I encountered following challenges while creating this submission: 

I) I have never done HTML, CSS, and JavaScript before, so it was a little bit challenging for me to grasp the syntax of these languages. For instance, in HTML I did not know how to comment something out or in JavaScript, I did not know that we must use "var" keyword to declare variables. To tackle these challenges, I used w3w schools website to do their "Try it for yourself" small coding exercises. These exercises were short and super useful for me to understand how the basic syntax of these languages work.  

II) I also had issues with my code while calling the start and stop function in the HTML file. My start button was not getting replaced with the stop button upon clicking. I debugged for a while and then I referred to the CodePath pre-work snippets. I realized my code had some extra default lines in the HTML file that were not allowing my start button to be replaced by anything else. Once I removed those default lines, my code worked fine.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I have quite a few questions about web-development after doing this pre-work. Firstly, I am curious to know how a website works that has more than one page. Does having more than one page mean we need separate HTML, CSS, and JavaScript files for each webpage or is there a way to write code for all pages of a website in one CSS, HTML, and JavaScript file. Secondly, Other than JavaScript what kind of other programming languages can I use for web-development and which platforms other than Glitch can be used to develop websites. Lastly, how does the role of a full-stack web developer is different from that of front-end or back-end developer? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, then I would add a function in JavaScript that would display a new message to the user every time they click a game button. For instance, if they are doing well in the game then every time, they get a cue right my game would display messages like “Well Done!”, “You are super close to winning” etc. In case, if a user is getting wrong cues, then my game would display messages like “Try it one more time! I know you can get it right etc.” I would also add different levels to my game in a way that each level would correspond to a certain speed of the game. In that way, my user can select at what speed they want to play the game. For instance, if my user selects level 1 then they would be playing at lower speed as compared to level 2, 3 or so on.



## Interview Recording URL Link

https://youtu.be/ajYq4j72nL0


## License

    Copyright [Kashaf Mujeeb]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
