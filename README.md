# Pre-work - *Memory Game*


Submitted by: Prentice Jones

Time spent: 5 hours spent in total

Link to project: 
https://glitch.com/edit/#!/cultured-mountainous-bream
https://cultured-mountainous-bream.glitch.me

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)


![](gif1-link-here)![](https://i.imgur.com/s8WXx6o.gif)

![](gif2-link-here)![](https://i.imgur.com/6BgC1AX.gif)

![](gif3-link-here)![](https://i.imgur.com/DK56Bog.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.w3schools.com/cssref/css_colors.asp
https://www.w3schools.com/csSref/css_selectors.asp


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I particularly had a difficult time implementing the logic of the guess function. I am a visual learner so the flow chart helped me to write out the code. However, at first, the first cue would only play and when the user pressed the correct button nothing would happen. I knew that this meant progress was not being made and something must have been wrong with my nested conditionals. I wrote the diagram from scratch and then wrote out the corresponding pseudo-code to match it. I noticed looking back on the original code that I had not fully understood the difference between the guessCounter and progress variables. After I had verified one was to keep track of the user’s place in the clue sequence and the other to represent the length in terms of guess I rewrote my code. Afterward, I was still getting the same error and so next I went through my logic again compared to my actual code. When everything seemed to make logical sense I started to look at the brackets and my guessCounter was not in the correct scope to be incremented. After I adjusted the bracket I went through each statement to double-check my code.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I am very interested in the process of web development. I am most familiar with Java, C, and Python and have not had the opportunity to thoroughly develop and enhance my skills related to application or web development. At school we usually are meant to complete projects individually and if we need help go to office hours. However, I know that in the industry people mostly work in teams. For that reason, I want to know more about the flow and timeliness of completing projects. Additionally, I would like to explore what is directly applicable to what I have learned through this project. For instance, are Javascript, HTML, and CSS typically the tools in web development, and if not what platforms are used more.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project I would like to work on implementing features that would add higher stakes for the user. I was interested in the optional feature to randomize the pattern of the buttons so that when the user interacts with my game there is no way to beat the game simply by memorizing the order of the buttons. I found myself starting to become used to the sequence of the pattern array even after I added two additional buttons. I am already familiar with the Math.random function in java and am always curious to learn about the comparisons and nuances of the similar or same functions across programming languages.



## Interview Recording URL Link

https://vimeo.com/695115026


## License

    Copyright Prentice Jones

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
