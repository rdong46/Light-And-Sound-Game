# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Ricky Dong

Time spent: **10** hours spent in total

Link to project: https://glitch.com/edit/#!/nonstop-smart-octave

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
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- User imput to determine how long the sequence should be(ensured that no negative number or letters can be entered)
- A display that showcases the number of lives you have remaining
- A notification that you lost a life followed by the same sequence playing again

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Entering the length of the sequence and starting the game.
![](https://cdn.glitch.global/57a9442d-41b2-4b81-bff0-da3def2ff268/test9.gif?v=1648602090992)

Winning the game.                    
![](https://cdn.glitch.global/57a9442d-41b2-4b81-bff0-da3def2ff268/test10.gif?v=1648602091131)

Making a mistake and getting notified that you lost a life and losing the game.
![](https://cdn.glitch.global/57a9442d-41b2-4b81-bff0-da3def2ff268/test11.gif?v=1648602091075)

Sound Playing when you click on each of the buttons.
[Click Here](https://www.kapwing.com/videos/6243ad44c1f09a0065966829)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- stackoverflow.com
- w3schools.com

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

There were a couple of challenges that I faced while creating this submission. Most of them involved my attempts to understand more deeply and conceptually what each part of the code does. My main challenge that I encountered was when I tried to understand how each separate file connected to one another. I was very intrigued on how the HTML file, the foundation of the website, then can be connected to the CSS file, the design of the website, and finally tied together with the JavaScript file, the functions behind the website. For example, when I implemented a display that shows the user their remaining lives, I was puzzled on how I was able to physically change the HTML file within the guess function, which is part of the JavaScript file. I was able to find the solution on stackoverflow.com, which showcased some very basic examples of how JavaScript can change the text in an HTML file. I tested different ways and ended up learning that in a JavaScript file, you have to  access that particular HTML element you want to change and then change its innerHTML to display a variable that changes as the code runs. Similarly, this problem also occurred when we had to implement a function where the buttons change color whenever we click on it. This not only involved the connection of the HTML and JavaScript files, but also the CSS file. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing the submission and thinking about improving the game, I began to notice that I am very limited in what I can do with my current knowledge of web development. For example, I was thinking of implementing a new mode where the user’s high score gets displayed, setting a goal for the user to hit and beat. However, when thinking of how to implement it, I was unable to understand ways to save the user’s personal high score to where if he leaves the game and then comes back, his high score still remains. I have seen other websites use cookies to save personal individual data, but I was still wondering if there are other ways in which we can save local data, in my case an individual’s high score, without affecting the global data, in my case another user’s high score? Similarly, how do websites allow different users to access the website at the same time, yet display different things according to the individual user? Another question I had on web development included the concept of adaptability of websites and how they can function based on the platform the user is viewing it from? I have seen websites where it changes based on whether I view it on my computer or on my phone, so I’m really curious about how it works. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would try to implement a mode where the sequence keeps building until the user uses up all three lives. As of right now, the current game lets the user set the length of the sequence. Once the user completes the given sequence without exhausting all his lives, they win. Otherwise, if they fail to complete the sequence, they lose. In this new mode, the user does not set the length. Rather, the game keeps going, keeping track of the length of the sequence. The game would end when the user uses up all three of their lives. I would then implement a high score system in order to set a target for the users to reach when they play the game. Additionally, I would spend some time learning what makes a good UI/UX design for the game and then clean up the game, making it more aesthetically pleasing. As of right now, the overall game design looks very disjointed and not fluid, making the user experience unfulfilling. This includes making the game functionable from different devices with different sized screens.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/98c57cf37cfe4733bbfa84cf274f0b01)


## License

    Copyright Ricky Dong

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
