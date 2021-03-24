# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **NAME**

Time spent: **8** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![Video Gif](http://g.recordit.co/zClUBOsI4B.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
None

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

When I was working on the prework, there were a few problems that I encountered, but the most challenging problem that I encountered is the typo that I made. Some people may think that typo is not a big deal at all, but when I was making the memory game, I spent hours debugging because of a typo. The Glitch website only shows if my variable has never been declared before, but it did not show the error if I wrote the name of the function incorrectly when I ran my code. I did not know this before, so when I saw the program does not perform as I expected, I was really confused because I followed every step of the instructions. Since everything made sense to me, I started to look at the beginning of my code, and make sure my code matches with the instruction of the prework. After I went through my code, the error still there, so like other programmers, I asked myself if I made a dumb mistake or not. So I looked at each line in the Javascript file to make sure I called their method correctly, and commented some functions of the stop and start buttons to see where the code crashed. After I identified where my code behaved incorrectly, I copied a different line of code and replaced the one that had a problem with it. After I fixed the problem, I undo the previous step to see the differences between those two lines of code even though they are basically the same. Then I saw that the difference between those two lines was just one character; I was speechless. After I told myself to type slower, I didn't waste time to find a type mistake, which was hard to find. The typo mistake taught me a lesson that always double-checks a part of code before moving on or I will waste my time.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After I completed the prework, I was wondering, “Why does web development have so many frameworks and languages?” Before I learned about web development, I was into mobile development, and I worked mainly with Swift. However, in mobile development, I don’t use a lot of frameworks, so when I got into web development, I surprised about the fact that there are so many frameworks to use to create a website, but that’s also became an interesting thing because I can learn new things from these frameworks and optimize my code with them. Another question that I have is, “Why does it cost so much money to maintain a website?” I know some websites allow people to host their website for free but not with a custom domain. Each month, many companies need to pay hosting services to maintain their websites, so I am not really sure why many companies don’t create their own hosting services but have to go through these hosting services.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I have more time to work on the prework, I will try to figure out a way to make my code shorter and also make an animation with music when the player wins or loses the game. I believe that a winning or losing animation will make the game become more interesting. To create the animation, I will use CSS animations and JavaScript animation. Animation could make the website run slower, so I need to create an efficient animation. Therefore, I plan to use requestAnimationFrame because sometime, I don’t really know how long the browser will take to draw a particular frame. So, requestAnimationFrame allows the browser to redraw and call the function before that frame gets to the screen, but I need to make sure my animation is time-based instead of frame-based, so I can keep track of my animation time. If requestAnimationFrame does not work, I will change to Animator.js, a simple and easy to use animation library with a focus on avoiding scope-creep.
