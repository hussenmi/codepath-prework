# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Hussen Mohammed Ibrahim**

Time spent: **4** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![Working correctly](http://g.recordit.co/CVSVMO6FP7.gif)
![Game over](http://g.recordit.co/V5PUkF5rvC.gif)
![Random pattern](http://g.recordit.co/62wqj0limn.gif)
![](gif4-link-here)

## Reflection Questions
1. **If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.**

W3schools resources are very helpful and well organized. It has examples and “try it yourself” sections for most of their explanations. These helped me clarify a lot of concepts.
I also used a medium article and a StackOverflow post to help me clarify the different variable declarations in JavaScript. Coming from Python, where I didn’t need to choose my variable type, this was a new concept, but those articles clarified the concepts.

    1. https://www.w3schools.com/html/
    2. https://www.w3schools.com/js/
    3. https://www.w3schools.com/css/
    4. https://medium.com/@sahelasumi/difference-among-var-let-and-const-in-javascript-e98725076601
    5. https://stackoverflow.com/questions/762011/whats-the-difference-between-using-let-and-var


2. **What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**

In creating this project, I encountered a couple of challenges. Firstly, following the guide on creating the game, since I was following what was given and there were quite a few things to keep track of, I had a bit of a hard time making sense of it all at once. For example, there were variables like cluePauseTime, clueHoldTime, guessCounter, gamePlaying, progress, and so on. At first, I was just copy-pasting the given code to my editor and using it without actually thinking about what exactly each variable was tracking or why I was using a certain snippet of code. I realized that this was happening because I didn’t have a mental map of my variables and I wasn’t keeping track of them. I overcame this problem by ***thinking before doing***. This may sound trivial, but it’s really impactful. This allowed me not to jump into the code straight away, but to take some time to try and process what the given code is doing – read it, understand it, and internalize it. This allowed me to create a mental map of what every part of the code is responsible for and thus if I had to alter a specific part, I could just change that. But more importantly, it allowed me to internalize the code and think about it thoroughly. 
Another challenge I faced was where the different ideas that were being introduced in the prework step by step would fit into my understanding of these languages. For example, when the setTimeout function was introduced, I was thinking of the other in-built JavaScript junctions that I know of. I googled a couple more and read about them on StackOverflow and understood what type of problems could be solved using JavaScript’s in-built functions. Because, if this wasn’t introduced here, I wouldn’t have guessed this kind of function would be in-built. But a good takeaway I got from this is to always search for solutions, and try to get our hands dirty. Because the only way to get better at it is by doing it over and over again, by getting our hands dirty. In conclusion, the main challenge I faced was creating a mental map of the project and what the different snippets were doing and I solved that by taking the time to actually go through it a couple of times before jumping straight to the coding.


3. **What questions about web development do you have after completing your submission? (recommended 100 - 300 words)**

In this project, I saw the very basics of HTML, CSS, and JavaScript but these technologies by themselves are not enough to build a full-stack web application. We need different components like frameworks, databases, etc. My main question now is how do we use frameworks like react in conjunction with what we saw here? How do we store data we get from users or data we fetch from somewhere else? Basically, how do we use databases in conjunction with our websites? And how do we even go on about creating a mental image of where everything falls in place when creating applications that use different technologies together. Even with just HTML, CSS, and JavaScript, they were interacting with each other, so I want to understand how the technologies of creating a modern web app interact.
I also want to understand what kind of features already have in-built methods that we can use, For example, a lot of websites have user authentication, so some in frameworks, there is an in-built method that would allow the developer to easily authenticate the user. I want to know what kind of methods are so mundane that developers don’t need to create them from scratch because the frameworks already provide a way to do those tasks.


4. **If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)**

If I had more hours to work on the project, I would focus on making it more personalized for the user. I would first include a feature that would allow players to create a user profile. I would then create different difficulty levels (easy, medium, and hard). I haven’t decided the specifications of each level but they would be divided along the lines of how many buttons would be available, how fast the turns are and how many strikes a player gets. After a person creates a profile, for each game, they would be able to choose the number of buttons they want. The game then dynamically creates the requested number of buttons with different sound frequencies. Every game is also instantiated with a random pattern generated after the user inputs how many buttons they want in the game. I also want this to be a fun way that users can interact with their friends, so it would be nice to have a way that they can share their high scores with their friends by sharing it on social media. This can be done by connecting it to sites such as Facebook, Twitter, WhatsApp, etc. I currently don’t know how to do this, but I feel like it’s a good opportunity to learn about this topic and this is why I like learning by doing because it helps to make it stick. I also want this game to be used in enhancing the players’ memory capabilities in different ways. Therefore, the user can choose if they want the buttons to change color only, sound only, or both. This will allow them to strengthen whichever skill they desire to do so. This will allow users to recall a pattern using less information if they choose to do so, which is a useful skill.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/f3fed85cf2e4488a8adadbf7a0461c39)


## License

    Copyright [Hussen Mohammed Ibrahim]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
