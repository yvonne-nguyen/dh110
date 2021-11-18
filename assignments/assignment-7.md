# Assignment 7: Interactive Prototype 
Yvonne Nguyen | DH 110
---
## Purpose
My project is centered around an app that assists users in finding and scheduling a vaccine. The purpose of an interactive prototype brings one's design "to life". Through creating an interactive prototype and asking users to test it (e.g., via through a cognitive walkthrough), one can get a gist of how a user will use one's product.  

---

### Tasks That This Prototype Supports
1. A notice that lists the information the user will need in order to successfully schedule a flu vaccine.
2. The user can select which type of vaccine they would like to schedule.
3. The user can input their address and select their perferred distance of the vaccination site's proximity. 
4. The user can filter and sort the results of vaccination sites.  
5. The user can schedule a vaccine of their choice through selecting which time and date they would like.
6. The user can fill out their personal information, their insurance information, and their primary physician's information. 

---

### Link 
The link to my interactive prototype can be found [here](https://www.figma.com/file/EkkyhsjrsY9pp6xjSA3D2a/dh-110?node-id=56%3A5)

![interactive prototype screenshot](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/interactive-prototype.png)

---

### Cognitive Walkthrough 
The link to my cognitive walkthrough can be found [here](https://youtu.be/lLVbFarRy7o).

I conducted my cognitive walkthrough with my parner Justin. We used Zoom to record our session. We also used Zoom's screenshare feature so I can have a recording how he interacted with my prototype. 

#### Summary of the Cognitive Walkthrough
1. Justin completed the tasks (i.e., (i) schedule a flu vaccine and (ii) use the sort and filter options) seemlessly. 
2. Throughout the tasks, I asked him some questions about some error mistakes I could imagine another user making (e.g., selecting the wrong vaccine) and asked him how he would change that.
3. He did not use all of the interactive options I implemented: (i) using the bolded "Relevence" from the results screen to get to the sort screen and (ii) the little dots from the 'progress bar' from the filling out one's information section). 
4. Justin recommends that I add an option for the user to select their preferred date for their vaccine on the page they input their address. 

---
### Iterations 
Based on the feedback I got from my classmates and from my impression test, I made some iterations to my design. 

#### Font
Based on the limited options with the previous font I chose (Arial Rounded MT Bold), I changed my font to Comfortaa. It has the same "feel" that I was going for (i.e., friendly), and it also has a "bold" and "regular option"!

This is the previous font I used, Arial Rounded MT Bold.
![old font](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/old-font.png)

This is the font I currently use, Comfortaa.
![new font](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/new-font.png)

#### Button Size
One comment that stuck out to me during my peer review was the size of my buttons. I decided to make them bigger. 
The dimensions of my previous button was, 130x38 with a 2px inside stroke.
Now, the dimensions of my new button is, 125x50 with a 2px center stroke. 

The button on top is my old one. And the component on the bottom are my new ones.
![buttons](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/buttons.png)

#### Components
I learned how to use components and variants recently and it's a super cool feature. Initially, I wanted to have an option for users to hover over a button, and once they hover over it, the color changes. This is because I wanted to reinforce to the user that the button is "clickable". However, prior to learning about how to use components, I made a new screen for every interaction (i.e., one screen for the vaccine selection page and one screen showing that the flu vaccine is selected). This, when it came to the filling out one's information page, got *extremely* cluttered. For reference, my new iteration has 20 screens while my initial design has 36 screens. Initially, when I tried to implement the “hover” feature, I used overlays. But I ran into the problem of the page being “static” (i.e., I cannot click on the “back” or “next” buttons). Afterwards, I tried using components and variants but I got really confused because what I wanted to implement would not manifest. I felt as though I was on the right track, but I was missing something. I ended up asking Professor Cho for help. Turns out, I needed to add the interaction to the variant from inside the component box, and not add the interaction to the component on the screen (what I was doing before). This was really confusing, but now I feel as though I have a firmer grasp on how to use components and variants. 


![components](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/components.png)

#### Drag
When I was half-way through my iteration, I realized that what I was designing is a mobile app. This whole time, I was testing out my product via my laptop. I downloaded the Figma Mirror app and I tested out my prototype on my phone. I found myself performing certain "muscle memory" gestures from using my phone. One was dragging left to right in order to go to the previous page. I decided to implement that to my design by adding a rectangle to the left side of my screen and made the opacity 1%. For the interaction, I used the "drag" feature (with the animation set to "push" and 'push left'). 

![drag](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/drag.png)
