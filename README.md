# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Charidi Stevens

Time spent: 22 hours spent in total

Link to project: https://glitch.com/edit/#!/prickle-hickory-brazil?path=README.md%3A7%3A14

## Required Functionality

The following **required** functionality is complete:

* [✔︎] "Start" button toggles between "Start" and "Stop" when clicked. 
* [✔︎] Game buttons each light up and play a sound when clicked. 
* [✔︎] Computer plays back sequence of clues including sound and visual cue for each button
* [✔︎] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [✔︎] User wins the game after guessing a complete pattern
* [✔︎] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [✔︎] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [✔︎] Buttons use a pitch (frequency) other than the ones in the tutorial
* [✔︎] More than 4 functional game buttons
* [✔︎] Playback speeds up on each turn
* [✔︎] Computer picks a different pattern each time the game is played
* [✔︎] Player only loses after 3 mistakes (instead of on the first mistake)
* [  ] Game button appearance change goes beyond color (e.g. add an image)
* [  ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [  ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [  ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![](https://i.imgur.com/zd7v4bx.gif)

![](https://i.imgur.com/ojkqkwC.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
	 - www.w3schools.com
	 - [HTML | Codecademy](https://www.codecademy.com/learn/learn-html/modules/learn-html-elements/cheatsheet)
	 - www.stackoverflow.com
	 - [GeeksforGeeks](https://www.geeksforgeeks.org)
    

2. What was a challenge you encountered in creating this submission (be specific)? 
How did you overcome it? (recommended 200 - 400 words) 

    While creating    this submission I ran into a couple of challenges some that 
I found a solution too and some I did not. If I remember correctly the first 
problem that I had was my attempt to change the speed of the clue playback. As 
instructed, I updated the “clueHoldTime” var to decrement for each playback,
in result the playback did change in speed but did not play the pattern 
completely. I decremented by 100 so I believe that caused the var’s value 
to get too small too fast which caused that sequence to stop before reaching
the end.  After plenty of test runs, I found that decrementing by 25 allowed 
the program to change in speed throughout the whole pattern.

    Another challenge I encountered was creating a random array pattern for the 
sequence. Essentially the problem was that my program which create an array 
of number from 0 to 5, this caused the clue playback to sometimes not play a 
button if 0 was randomly chosen in the array. What I needed was for the array 
of number from 1 to 6 and I that by adding 1 to each number generated.

    Adding a p


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 




## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Charidi Stevens

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.