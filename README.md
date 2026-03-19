# CSS

## Week 1

### Introduction exercise

What did I do today?

- I read up on scroll animations and made my section of the website of my team. There I animated clouds on scroll to translateX, the sun on scroll on a path and the birds to loop flying on a path. I also added a text gradient animation on the heading of my section.
  <img width="1582" height="802" alt="Bildschirmfoto 2026-02-18 um 16 03 06" src="https://github.com/user-attachments/assets/04cb1a50-2cf0-4623-98ff-963b77ab735e" />

How long did it take?

- The whole day, 7 hours

What did I learn?

- How to actually use scroll driven animation, a little bit about animation-timing-functions and also that scroll animation is really hard to get right

What will I do tomorrow?

- Add some finishing touches, think about how to explain the code I wrote and what would be interesting to people. Merge all branches together for the website.

### Day 1

What did I do today?

- Presentation about the introduction exercise
- I chose the silly walk as my final assignment, so I followed a tutorial by Julia Miocene because I want to learn to make CSS illustration and animations like her
  ![Tutorial](assets/readme-images/tutorial.png)
- Then I thought about that I wanted to make a silly walk with a character from an animated series I watched in my childhood. I wanted to use Maja the Bee so I made her in Figma to see how I would make her out of different CSS blocks
  ![Figma](assets/readme-images/figmaschets.png)

How long did it take:

- The whole day

What did I learn?

- How to make an HTML illustration with just divs and using different background colors and box shadows. I didn't even know you could use more than 1 box-shadow.

What will I do tomorrow?

- Try to make Maja the Bee in CSS to start animating it

### Weekly checkout

This week I learned a lot during the introduction exercise. I already did Cyd's workshop on scroll animations but this was the first time I actually used it. And it turns out, it's quite hard! I struggled a lot to actually get things to look the way I want it them to look. I suppose I'll have to spend more than one day to actually understand the animation timelines.
Other than that I didn't start on my code yet for the final exercise but I am happy with my idea. I'll make Maja the Bee in CSS and then make her walk silly! I think other than the animation my biggest challenge will building my Maja from CSS and actually making her look nice.

## Week 2

### Day 2

What did I do today?

- I spend the whole day on making the outline for my skeleton in CSS. I had already made an HTML outline, and I went off of that in my CSS. I tried to work with variables, that would make the body stay in ratio to itself. I also decided that I would use basic shapes first and then do the actual design of Maja the Bee later.
  ![Variables](assets/readme-images/variables.png)
- When I finally had my whole body outlined, I already tried to see if I could move the body the way I wanted to. I didn't animate yet but I just used transform: rotate(); to move one leg. I realized that my initial layout didn't quite work so I spent quite some time rearraging divs so they would move together. I hope I can leave it like this now.
  ![skeleton](assets/readme-images/basicskeleton.png)

How long did it take:

- The whole day

What did I learn?

- How to nest properly when animating a whole skeleton

What will I do tomorrow?

- Try to work more on actually making it look like Maja the Bee and then start animating

### Day 3

What did I do today?

- I thought I figured out how to do the structure of the skeleton, but when I transformed elements, my z-index structure broke. I asked Nils about it, and apparently I have to redo my whole skeleton. Apparently I couldn't leave it like this. Sad. But I tried again and figured out a HTML structure that works (again, hopefully).
  ![skeleton2](assets/readme-images/skeleton2.png)
- I decided to use layers to work from my basic structure towards my Maja the Bee. That way I can keep the basic styling and can keep going back to my begin point if I want to.
- I finally finished all my styling so my transforms and animations don't break the structure. I started on the animation but I did it a really complicated way and and the end of the day Nienke showed me how she works with @property and I realized that I also need to implement that. So time to start doing that next time.

How long did it take

- the whole day

What did I learn?

- finally how the skeleton structure works

What will I do tomorrow?

- implement @property finally annimate!!

## Week 4

### Day 4

What did I do today?

- I animated!! and first I started by using keyframes, but after following Sannes workshop about container queries, I decided to use a slider and transform the skeleton with the values of my slider. So I did that the whole day and I finally have 3 steps in my silly walk animated and transformed!!
- I did get really frustrated again because this whole subject long I had problems with the z-index and skeleton structure and then I animated.First I added a bunch of keyframes for every step but that took ages!!
  ![wronganimation](assets/readme-images/wrong-animation.png)
  And then I realized through talking with Nienke there was a better way with properties and did it all over again and then I decided on the slider transforms and did it all over AGAIN. So it feels like I am not very far, and only the last hour or so have I productively worked on doing something that I can probably just use for my final product, UNCHANGED.
  ![properties](assets/readme-images/properties.png)

This really is a learning process.

- I also followed Cyds workshop "gekke dingen in CSS"

How long did it take

- the whole day

What did I learn?

- How to work with the slider values and copple my transforms with custom properties to the values. And I finally transformed annd started on my silly walk :)

What will I do tomorrow?

- more steps to my silly walk, hopefully the styling for my Maja the Bee mode

### Day 5

What did I do today?

- Today I worked on step 3 until 11 of my silly walk and finished it! It is now completely slide and transformable!
- I also followed the maths and variable fonts workshops
- Inbetween and afterwards I also worked on implementing a font (I used comic style fonts because I am using a cartoon character) and I also started working on my design for my second mode, not the skeleton mode but Maja the Bee! Finally.
  ![skeleton3](assets/readme-images/skeleton-final.png)
  ![majathebee](assets/readme-images/majabegin.png)

How long did it take?

- Workshops: 2 hours
- Styling and transforms: 3,5 hours

What did I learn?

- That @layer doesn't work the way I want it to. And that maybe my life would have been easier if I had just used :has for the different themes.

What will I do tomorrow?

- Finish my Maja the Bee styling, do some more fun stuff with fonts, maybe add a background

## Weekly check-out

During the check-out, Sanne recommended that I could add a second mode in which the animation is not driven by the user input but is just running by itself. Also that I could add some animation to the wings and a possibility for easter eggs with which I could rotate my bee. So I'll have to see what of that I can incorporate next week! I also still need to add something to make my font more fun and possibly interactive. Because this is all i have for now:
![font](assets/readme-images/font.png)

## Week 5

### Day 6

What did I do today?

- I added a checkbox (and styled it as a slider) for my second mode, which I made an animation mode. For that I translated my transforms into keyframes. That didn't work properly in the beginning but apparently that is because defined my properties the value of 0 sometimes, when I should have given it 0deg. But I changed all that and now it works!
  ![animation](assets/readme-images/animation-mode.png)
  ![keyframes](assets/readme-images/keyframes.png)
- I also added a small animation to make the eyes blink and the wings flap every now and then. I wanted to move the two wings seperately, but I made the second wing a box shadow so it moves with the first one..oh well.
  ![wings](assets/readme-images/wings.png)
- I looked online what kind of open source variable fonts there are and I found RobotoFlex so I decided to use that in my project.
  ![variablefont](assets/readme-images/variablefonts.png)
- I also added easter eggs to my website! I have two invisible buttons now on the right and on the left side of the page. One of them makes the bee very small by changing the root size and one of them makes the bee fly away, I am very happy with that one.
  ![majasmall](assets/readme-images/maja-small.png)
  ![majagone](assets/readme-images/majagone.png)

How long did it take?

- the whole day

What did I learn?

- How to work with variable fonts! I had never done that before and it was interesting to see what kind of properties I could play with and how.

## End reflection

- I learned a lot during this subject! One of my learning goals was animation, because I had neglected animation a little bit so far in my coding journey. And I definitely learned using animations and transforms in this project. Also animating characters was something that has always intrigued me, I already had some experience doing it as drawings, frame by frame, as well as in Adobe After Effects. But I really wanted to learn how to bring a character to live with code and I am happy to report that it worked. 🙂
- What frustrated me most was definitely getting the skeleton right so I could animate and transform the limbs without breaking the z-index. And I had to learn how to do that because my character in mind in side-view and of course then I couldn't go back on that because once I have an idea I have to keep trying until it works. But after a lot of trial and error I finally have a skeleton structure that works. I am not sure if I could immediately and perfectly recreate it in the future but I do have more of an idea where to start and also where to look when it goes wrong.
- Another frustration came up when I wanted to start animating. At first I didn't really understand the rotation origin so that was also a lot of trial and error before my limbs rotated in the spot that I wanted them to. But once I had figured out where to put the rotation origin of the limbs, the actual animation part went pretty quickly. I basically did all the 11 steps of my silly walk in one day, once I had all the structure down.
- During my project I tried to use layers, and I did, but I have to say I am sure I used them not quite in the way they were intended and I am also not quite sure I really understand the way they are intended. I started out by first making a very simple character with no details, animated that, and then I added another layer in which I basically just did the extra styling to make the character look like a bee. If I turn around the layer structure I can now still see the old character, which is cool I guess, but I'm not sure if it's actually useful.
- I do like the way my character design turned out in the end. It obviously doesn't exactly look like Maja the Bee but if you know if you can tell? It's a cute bee, just a bit more human like. I learned a lot in the tutorial by Julia Miocene, about using box shadows to create shapes that make up my character, so not every tiny detail has to be it's own <div> element. I used that also with my character, to make the hair (I even used a slightly bigger box shadow to make the black outline) as well as the nose and the wings and I am really happy with how that turned out! I'm really excited to see how much more illustration I can do with CSS that seems really fun to me.
- A big thing I learned in this project also is using @property, which I had honestly never heard of but it made my life so much easier!! What a useful feature. At first I was adding animations single-handedly to every body part and then suddenly I could just make some variables and animate those and not bother about the body structure anymore. What a blessing, especially in a world where using classes isn't allowed. 🙃 So that was very cool to learn.
- Another thing that I actually used for the first time was using calc(). And I am also kind of sure that I now used it in placed where I also kind of didn't need it, but it was really cool to think of how I could make every part of the body relate to another. The arms are twice the length of the head. The rotation origin is half of the arm width. The legs are 3/2 of the arms. Stuff like that. If I were to skale down one thing everything else would change in relation to it, and isn't that just cool.
- I had also never heard of variable fonts before. I didn't have too much time for it anymore in the end, otherwise I would have probably made the font look even cooler and respond more to the animation of the character, but I am happy to have learned how to use then at all and that they exist. And it does look kind of funny now, and I am happy about how the font becomes italic when the body rotated as well, like they're both leaning forward. I had fun!

## Bronnen

- Skeleton structure by Nils: https://codepen.io/enbee81/pen/ByLKLOQ?editors=1100
- Skeleton structure by Julia Miocene: https://miocene.io/post/css-character-skeleton/
- CSS character design: https://www.youtube.com/watch?v=LKwbGLv1Re4
- Walk cycle by Sanne: https://codepen.io/shooft/pen/myrbrGa
- Fancy border radius: https://9elements.github.io/fancy-border-radius/#70.51.68.51--474.374
- :after border https://stackoverflow.com/questions/28033616/adding-box-shadow-to-a-after-pseudo-element
- Variable fonts https://v-fonts.com/fonts/roboto-flex
