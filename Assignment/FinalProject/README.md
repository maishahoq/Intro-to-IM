
                                                         Happy Panda Project 
                                                (Plushy Toy for Mental Health Support )


***     

The P5JS Link: (__)(https://editor.p5js.org/maishahoq/sketches/2krDoMj8j)

***   


### Inspiration

<img style="float:center;"  src="https://miniso-bh.com/wp-content/uploads/2020/05/0300021151_1.jpg" alt="Inspiration" width="500"  />

Mental Health: Main Part

Awareness About Pandas’ Extinction: Ending Part
Just at the ending screen, we will have 
Speech recognition [extra f we have time]

Range of good Heart State: 70 BPM to 90 BPM
### Design Explanation

# **FINAL PROJECT DOCUMENTATION** 🎨🔮✨ #

**///design concept & logo///**

- After thinking over the UI design, We decided to stick with two primary colors (warm pastel yellow (252, 238, 184) and white (255,255,255) for the clean minimalistic look. 


- We designed the Panda logo on iPad's Procreate app. First we made a rough sketch of the panda, and followed up with more layers to polish.

<img src="https://user-images.githubusercontent.com/90750426/168308861-ebef65c0-b7cc-474f-85bc-00bbb26b7159.jpg" width="300"> <img src="https://user-images.githubusercontent.com/90750426/168308792-2bc111a4-a91f-4930-8cfb-bc69ef901b99.png" width="300">


**///font choice///**

- We chose Helvetica Oblique and Million Dreams as our main two fonts. Since Million Dreams was the fancier one, we used that for the Logo and Menu options.
Helvetica, on the other hand, is neat and easy on the eyes, so we thought it was a good choice for directions and instructions.


<img src="https://user-images.githubusercontent.com/90750426/168308495-2f73cb99-6185-4e11-b0f6-1a0ded333e4b.png" height="200"> <img width="400" alt="directions" src="https://user-images.githubusercontent.com/90750426/168314081-c9824605-7be4-430c-b47d-bfcb6984cfa6.png"> 
<img width="300" alt="helveticaa" src="https://user-images.githubusercontent.com/90750426/168313254-84ba5da7-3f7f-473a-ac41-7e773582df8d.png">


**///design assets and shapes///**

- We designed all of our assets on Adobe XD and laid it out accordingly on the P5JS. In this process, Adobe XD's coordinate function helped us greatly in finding the right placements for the assets. For the shapes of our assets, we mainly sticked to rounded corners instead of sharper ones, which resulted in softer-looking aesthetic. 

<img src="https://user-images.githubusercontent.com/90750426/168311446-d621a384-5730-41a5-a31e-777dce24f32f.png" width="200"> <img src="https://user-images.githubusercontent.com/90750426/168311522-51c3378a-0de8-4536-a056-a2ac30f56171.png" width="200">

- For our background, we used a plain white background layered with stretch of tiles. This is a prominent design choice reminiscent of 2014 Tumblr era.

<img width="400" alt="tilee" src="https://user-images.githubusercontent.com/90750426/168315089-c017fb58-87f1-4556-bb8c-b4f05ac2da72.png">


**///additional design details///**

- We added triple heart detail on every page to complete the design. To make the hearts float and blink, we usec Framecount function.

<img src="https://user-images.githubusercontent.com/90750426/168315830-8c538cf9-2956-4675-af81-394949c35aa4.png" width="100"> <img width="363" alt="blink" src="https://user-images.githubusercontent.com/90750426/168315788-730f7905-17c5-41c6-b5fa-6f05df0ca318.png">

- Finally, we duplicated the panda on Procreate and drew a different version to make an animated one. We also created an animated gradient background on Photoshop, which loops during the meditation.

<img src="https://user-images.githubusercontent.com/90750426/168316679-52634c37-12b8-4948-b619-6d6feb9dc4c9.gif" width="200"> <img src="https://user-images.githubusercontent.com/90750426/168316892-e42dd523-90f7-4ee2-a8bf-3f7865bacadd.gif" width="200"> 

**///stitching process///**

to learn how to sitch, we followed [GitHub Pages](https://www.youtube.com/watch?v=K3fFHV6r9Ow) from Youtube. This video demonstrates an invisible stitiching method known as "ladder sititch." This was particularly helpful for beginners like us. After putting all the sensors inside, we made small cuts on the tips of the Panda's legs and hands. This way, we could get more accurate inputs from our sensors.





### Game Description

 Screens:
Start Screen
Panda at the bottom needs animation; If you click on this panda, we will be taken to a panda awareness screen.
Measure Pulse and Daily Mood Journal [Choose either]
If Pulse>70 and less than 90 BPM, normal category screen pops up
If Pulse<70 and > 90 BPM, non-normal category screen pops up
Screen-3:Click on anxiety tracker and it takes you to pulse measuring screen 
It will store all the pulse values for 1 minute, and give you the average pulse rate.
Based on the difference of the 1st and last pulse of every 10 sec interval, and if the average of these differences is greater than 30, you are very anxious; if less than 30, you are not anxious.
Pulse Screen

Pulse screen:
Non-normal category Screen:
     a. Breathing Meditation[Download Audio Files From Online] b. Guided Meditation [Download Audio Files From Online] c. Affirmation [Download Audio Files From Online]
           Normal Category Screen:
     Always end the cycle with a hug from panda


Daily Mood Journal: [Extra part]
       
    
The game will have two parts: `1.` Algorithm Visualizer
                              `2.` Algorithm Game

__Visualizer:__  This part of the game is instructional and was inspired from the assignment where we did generative art without any interaction from the user. So, there will be visualization of how the different sorting algorithm works based on which algorithm the user chooses.

__Game:__ This part of the game is interactive and was inspired from the assignment where we did generative art with interactions from the user. The user will be able to play the game and try out different algorithms by moving the objects on screen using the cursor.
+ Everytime a correct path is traced, a celebration sound goes off at the background
                              
    
   + __Screen 1:__  [Screen 1](https://youtu.be/-dmTamqtpMo)
   
   + __Game Play (If I Win):__       [Game Play (If I Win)](https://youtu.be/h-hNwFqHEBo)
   + __Game Play (If I Lose):__      [Game Play (If I Lose)](https://youtu.be/bYkFWa63nGk)




### Game Algorithm Explanation:


<img style="float:center;"  src="https://github.com/maishahoq/Intro-to-IM/blob/main/Assignment/GameDevelopment/Gallery/275042261_728017601908557_3536086805784017991_n.jpg" alt="Inspiration" width="500"  />








### Code Snippets:




+ Best Part of Code:

         + Game Modification:   The user can change the change just by changing the values in some of the variables, this will modify the whole code without it breaking anywhere. Example, just changing the no of balls variable, changes the box numbers, places the balls in equal distances, changes the comparisons of positions etc. The values have been barely hardcoded.
         
         + Resuse code from other assignments. I tried mofifying the one of the assignments to fit the game as an intro screen because the assignmnethas animation of balls to it.
         


### Encountered Problems




### Future Additions

__1__.  Adding an instruction animation using code. Due to lack of expertise and time commitment since I am overloading this semester and had a lot of exams and projects due at the same time, I could't do this before. I plan to add this during Spring Break.


### Reference



Website to used for colors: [Color Picker](https://htmlcolorcodes.com/color-picker/)

Mapping reference: [2.5: The map() Function](https://www.youtube.com/watch?v=nicMAoW6u1g)


Timer: [Timer using FrameCount](https://editor.p5js.org/marynotari/sketches/S1T2ZTMp-)


Audio Effects: [Oh No](https://mobcup.net/ringtone/oh-no-t6cf2k15/download/mp3)



### Questions:
How to stop taking values from arduino?
How to switch between multiple inputs from arduino?


### Roadmap
1. Get the 4 sensor data from Arduino
2. The p5.js 1st screen changes to 2nd screen after 10s of starting the program (cuz it takes sometime for the pulse sensor to start taking correct values as input) .
3. 