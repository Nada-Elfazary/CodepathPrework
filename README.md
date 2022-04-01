<<<<<<< HEAD
# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nada Elfazary**

Time spent: **5** hours spent in total

Link to project: (https://github.com/Nada-Elfazary/CodepathPrework.git)

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
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
I used the above link to figure out how the correct syntax for generarting random numbers within a specific range, which I used for the random pattern generation.

https://www.geeksforgeeks.org/how-to-change-an-input-button-image-using-css/
I used the above link to figure out how to make an image the background of a button

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge I encountered while working on this light and sound game was in implementing one of the optional features. Specifically, I struggled with adding images to the buttons when they’re clicked. I was able to add images inside the gameButtonArea div, and I was able to display and hide it depending on whether the button is clicked or not, respectively, by adapting the code for the start/stop buttons. However, I wasn’t able to make the image appear in the same place as the button. I tried changing the position of the image tag in relation to the other tags (essentially buttons) in the div area, but it still was not working. I decided to move onto other optional features and then come back to this if I had time at the end. 

After thinking about this for a while, I did a bit of searching online, which changed my way of thinking about how to implement this feature. Instead of removing the button and making the image appear, which seemed impractical and hard to accurately apply, the idea of making the background of a button an image rather than a color came to my mind. I then googled how to set the background of a button to an image and used that in my css file for when the buttons were active/lit instead of the color change. By giving this some time and having the chance to look at the problem again with fresh eyes, I was able to think of it differently and actually solve it.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I'm interested in knowing about advanced javascript libraries that facilitate the monotonous tasks of Web development to allow developers to work on more high level features. I am also curious about how web animation is implemented. Finally, I would like to know how this kind of work is divided among people and what different kinds of jobs web developers can take on.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. 


If I had more time to work on the project, I would work on making the interface more user friendly by adding more design and detail to the page. I would also change the tones produced by the buttons to make the sounds more interesting. For example, they could be pronunciations of labels for pictures that appear when the buttons are pressed. I also thought of slightly changing the sound and light memory game into something more complex that is based on the card matching memory game, but this would require me to look more into javascript and css features. Instead of the user trying to remember a pattern based on the lights and sounds displayed in order, the boxes (have to be an even number) could initially be all one color - for example gray - and then when the user clicks on a button it will change color or display an image, and they have to figure out what other box has that color/image when clicked. They get a few strikes and they keep trying until they match all the pairs. These matching colors/images will be assigned randomly for every game.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/gx_MtOWX1_0)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
