# Assignment 5: Interface Design 
Yvonne Nguyen | DH 110
---
## Purpose
My project is centered around an app that assists users in finding and scheduling a vaccine. The purpose of an interface design is to make the user's experience with using a product as "smooth" as possible. Interface design primarily focuses on the aesthetics of a product: typography, layout, color, etc. 

### Wireframe
This is a screenshot that provides a brief overview of what my wireframes look like. I cannot take a screen of all of my screens because I have over 20 and that would obscure the details on each indvividual screen. The link to my Figma prototype is [here](https://www.figma.com/file/EkkyhsjrsY9pp6xjSA3D2a/dh110-assignment-6%3A-high-fidelity-prototype?node-id=0%3A1).

![wireframe](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/assignment-6-1.png)

### Wireflow
![wireflow](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/assignment-6-2.png)

---
## Screen Design & Design System
### Typographic Variations
I tested out the fonts Arial, Arial Rounded MT Bold, and Dongle, respectively. Right from the beginning, I want my app to have a "professional" appearance. Therefore, I opted for a font that deemed "professional": Arial. However, Arial is, in my opinon, very bland. Next, I tried out Arial Rounded MT Bold. I really like this font because of the rounded corners. It makes the font have a more "warm" and "friendly" feel (compared to a font that has sharp corners). However, this typeface is only offered in bold (there isn't a regular, light, or italics version) so I was a bit hesitant on using it although I really like the friendly vibes it was giving off. I then went onto the Google Fonts website to look for another option. I chose Dongle because it resembles Arial Rounded MT Bold while having a “light” and “regular” option. However, Dongle felt a little bit too “cartoon-y” for me. It was deviating too much from the “professional” feel I initially wanted to go for. Therefore, despite only having one typeface option, I opted for Arial Rounded MT Bold. It looks professional, while having a warm and friendly feel to it. Since this font is only “bold”, I didn’t have to worry too much about lightness/heaviness. However, as I was designing and based on my impression feedback, I do have some trouble differentiating the header from the body text. My header is 50pt, with “header 2” being 22pt. The body text varies, from 16pt-18pt, depending on how much information is on a given screen.

![typographic variation 1](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/tv-1.png)
![typographic variation 2](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/tv-2.png)
![typographic variation 3](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/tv-3.png)

### Shape Variations
This screenshot captures 3 shape variations throughout my design. First is the circle used to indicate which date is being selected. I wanted to emphasize the date the user selected so they do not have to second guess which date they initially selected. I opted for a circle instead of a square because it feels more intuitive (to me at least). When I mark an important date on a calendar, I tend to circle the date instead of squaring it. The other two shapes are the “apply” button and the buttons for selecting which time the user wants their appointment to be at. These buttons are both rectangles but their roundness varies because I wanted to emphasize how they serve different purposes. The button for selecting the time is similar to the checkbox buttons throughout my design. I wanted this to emphasize select only one option because for the checkboxes, the user can only select one option. I wanted the design to be consistent. For buttons that are selected, the background color will change to the dark blue accent color. For further emphasis, I added a check mark to the checkboxes because it looks cleaner than just a dark blue box. 

![shape variation 1](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/sv-1.png)
![shape variation 3](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/sv-3.png)
![shape variation 2](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/sv-2.png)

### Color
These are my screens for light and dark mode. For dark mode, my background color is #2C2C2C and the text and accent color is #FFFFFF. For light mode, my background color is #FFF1DC, with the text color being #000000, and the accent color is #005492. I opted for a cream color for my light mode background because I wanted the product to have a warm feeling. I also tried using a light grey and it felt cold, so the cream color feels just right. I chose a dark blue for my accent color because blue has a calm feel. Initially, I wanted a lighter blue, but that color did not pass the color contrast accessibility test, so I ended up using this dark blue. 

![dark mode](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/color-1.png)
![light mode](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/color-2.png)
![light mode color contrast](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/color-3.png)

### Layout
My design has three layouts, “home”, “good”, and “results”, respectively. In hindsight, I probably should not use “good”. It was just the first world that came to my mind at the time. At first, I started off with designing a layout for my onboarding screen, but it turns out I needed a different layout for my following screens because those screens require more content. “Home” has 3 properties. The first contains 2 rows on the “top”, with the height of 80, offset of 30, and gutter of 25. The second the 1 column in the middle, it has the properties “stretch, with an auto width, and margin of 30. The last contains 2 rows located on the “bottom”, with the height of 40, offset of 30, and gutter of 150. The “good” layout emphasizes the lists of options (e.g., vaccine selection) the user will encounter. Each row then has each “section” of the list carved out. The “good” layout has A LOT (7 properties), but I will go over what the most important one. I have 13 rows, with the properties “center”, with the height of 67, offset of 0, and gutter of 1. The gutter size of 1 marks the place where the line that will divide each section would go. Does this layout need 7 properties? No. Making the layout is, in my opinion, the most difficult step. So I ended up playing around with it a lot and I ended up with 7 properties. The end result looks very nice so I’m too scared to delete anything. I will probably opt for less than 7 properties next time. Finally is the “results” option. Since my “results” screen has a scrolling option, my original layout cannot conform to the size of this screen because when I stretch my screen out, the layout rows move along with it. Therefore, I had to make a new layout specifically for that page. It is inspired by the “good” layout. This layout has less properties though (lol). It has 4 properties and the highlight is the 15 rows: it is “centered”, with the height of 110, offset of 0, and gutter of 1.

![layout 1](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/layout-1.png)
![layout 2](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/layout-2.png)
![layout 3](https://github.com/yvonne-nguyen/dh110/blob/main/assignments/layout-3.png)

---
## Impressions Test
The link to my impression test video can be found [here](https://youtu.be/XiRCqE7R6lg). 

For the impression test, I asked my partner Justin to help me. We conducted the test over Zoom. I sent him my Figma file and asked him to share his screen while he was looking at my prototype. 

### Summary
#### 1. Font Size Inconsistentcy
Justin pointed out how the “flu” option from the vaccine selection category is not the same font size as the other options. This was a mistake that I will fix later on.

#### 2. Dark Mode
Justin pointed out the cream color is a bit light and how he would prefer a dark mode. At the time I asked him to test out the prototype, I did not have a dark mode made. I made a dark mode option afterwards.

#### 3. Text Alignment 
On the screens that require the user to fill out their personal, insurance, and primary physician’s contact information, the text alignment for the the “filled in” options are not aligned.

#### 4. Text 
Justin said that the text on the “summary” page do not differentiate the header of each section from the body. Due to the nature of the font I chose, this is a problem. I can change it through making the typeface bigger. However, throughout the design process, I found this to be a major problem. I’m currently contemplating changing the font.
