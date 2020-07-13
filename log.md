# 100 Days Of Code - Log

### Day 1: June 5, 2020

**Today's Progress**: My first time using HTML and CSS. Worked on tribute page as HTML and CSS exercise. 

**Thoughts:** I learnt the difference between the CSS box-sizing properties, namely ```box-sizing:content-box;``` and ```box-sizing:border-box;``` This is useful when padding padding text within a ```div``` element.  

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 2: June 6, 2020

**Today's Progress**: Added a timeline to tribute page. 

**Thoughts:** (1) Producing multiple timline boxes has been an exercise in efficient coding. It is more efficient (and clearer) to create reusuable classes, than to create non-reusuable classes, which can multiply quicky when creating multiple repeating elements (such as those which appear throughout the physical progression of a timeline). 
(2) It's interesting dealing with a language which doesn't have an explicit ```if``` statement. (3) The ```:nth-child``` selector is awesome. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 3: June 7, 2020

**Today's Progress**: Worked on timeline. 

**Thoughts:** (1) Learnt the differnce between ```span``` and ```div``` elements. (2) It's intersting how position is altered by ```position: absolute;```. Also, to position an element with  ```position: absolute;``` within a container, that parent container needs to have  ```position``` set to  ```relative```.

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 4: June 8, 2020

**Today's Progress**: Read up on optimising repeating element layout. 

**Thoughts:** (1) While ```:nth-child``` is great, I've learnt that it needs to be applied to non-child classes which are all of the same level. I didn't originally organise my code in this manner, and thus I may need to backtrack and redo some stuff. Good lesson to learn for future projects. In this instance, I have created some easily reusualble segments of code with a couple of extra CSS styles to compentsate for the lack of ```:nth-child``` style automation. The net efficinecy of the code is equvalent, I think. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 5: June 9, 2020

**Today's Progress**: Worked on timeline and expanded it. 

**Thoughts:** (1) Back to PhD work now (labs are reopening at the end of covid). It will be a challange to keep up web development training alongside finishing my research. (2) A ```div``` element's background colour is not appearing at the end of the timeline. I can't figure out why. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 6: June 10, 2020

**Today's Progress**: Finished timeline. Started adding poetry section.  

**Thoughts:** (1) I've fixed part of yesterday's problem. I applied ```float:hidden``` to a div element, and I needed to add ```overflow:hidden``` to allowthe background colour to appear. (2) My log from day 3 has helped me solve a problem in seconds! This log is turning into an invaluable resource. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 7: June 11, 2020

**Today's Progress**: Learning how to make webpage responsive to changes in screen/window size. 

**Thoughts:** (1) I've been using the ```grid-column``` property, however, I think I need to do some background reading to use it properly. (2) I've been implementing some of the Flexbox Layout module features, and learning how to use them. This is a really useful tool. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 8: June 12, 2020

**Today's Progress**: Learning how to make webpage responsive to changes in screen/window size. 

**Thoughts:** (1) Learnt about media queries, and their use in tailoring style sheets to different devices. (2) Webpage is now responsive to a range of different screen resolutions.

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 9: June 13, 2020

**Today's Progress**: Learnt about CSS box model to greater degree. 

**Thoughts:** (1) I set width of a class to 100%, and didn't realise that this would overrule any changes to ```margin-right``` and ```margin-left```. Found the bug, fixed it, and now have a greater understanding of the CSS box model. (2) Found a great [colour pallet website](https://coolors.co/).

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 10: June 14, 2020

**Today's Progress**: Styling.

**Thoughts:** (1) I'm learning about buttons, and styling anchor elements to appear and function in the same way as buttons. Useful stuff. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 11: June 15, 2020

**Today's Progress**: Styling.

**Thoughts:** (1) I've learnt to use ```calc()```, an incredibly powerful tool for the calculation of distances using different unit combinations. (2) I'm having trouble learning how to position a box outside of it's parent element, and with a position relative to that parent element. I'm missing a trick and will find it soon... Got it: Give the parent element ```position:relative``` and the child element ```position:absolute``` and ```left/right:100%```.

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 12: June 16, 2020

**Today's Progress**: Learning about child element positioning within containers.

**Thoughts:** (1) ```calc()``` is  fantastic. (2) It's not straighforwad to make a ```div``` with width/height greater than that of it's parent. Nonetheless, problem solved. (3) Vertically centering a ```div``` (with ```height``` specified in pixels) can be achieved with the following: ```top: calc(50% - (height of element in pixels/2)px);``` (NB: include spaces either side of the mathematical operator).

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 13: June 17, 2020

**Today's Progress**: Understand more about grid layouts in CSS. 

**Thoughts:** (1) Made a responsive photo gallery within the webpage. (2) When organising photos into a grid, using ```grid-template-rows``` and ```grid-template-columns```, it's best to make ```div``` containers within each section of the grid, as this allows for greater flexibility, especially when using ```Flexbox Layout``` to wrappers. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 14: June 18, 2020

**Today's Progress**: Create an addition section with links to additional information. 

**Thoughts:** (1) I've learnt about using a ```<link>``` tag link to an external style sheet. Very useful for creating a links section to facebook or twitter pages etc.. (2) Vertically and horizontally align a child element by adding to following to it's parent:   

    display: flex;  /*Make the container a flex container*/ 
    
    align-items: center; /*Vertical alignment*/ 
    
    justify-content: center; /*Horizontal alignment*/ 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 15: June 19, 2020

**Today's Progress**: Debugging flex issues. 

**Thoughts:** (1) I noticed that when the centering solution described above was applied to the wrapper, it resulted in an inability to allow child elements to reshuffle as normal ```inline-block``` elements. Instead, the solution lay in chaging the centering of the wrapper from that described above (still suitable when the child element does not need to be inline-block) to ```text-align: center;```.

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 16: June 20, 2020

**Today's Progress**: Finished tribute page. 

**Thoughts:** (1) Read about the use of a ```main``` element and included it. 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)

### Day 17: June 21, 2020

**Today's Progress**: Started survey page. 

**Thoughts:** (1) Need to read more about webkit. (2) Added header and began establishing page organisation. I'm happy with how much faster I've become. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 18: June 22, 2020

**Today's Progress**: Debugging. 

**Thoughts:** (1) Came across the issue of collapsing margins. Solved problem by either adding ```overflow:auto;``` to the ```section``` in question, or by adding... 
```
  display: flex; 
  flex-direction: column;
```
  ... to the ```main``` element containing said ```section```. It should be noted that the latter works because there is no margin collapsing in flexbox. (2) Also, text wasn't overflowing to the next line upon webpage re-sizing. This was because the text container's ```width``` wasset to a fixed number of pixels. 
  
### Day 19: June 23, 2020

**Today's Progress**: Added an addisional section to the survey form. 

**Thoughts:** (1) Read more about the different iteration of webkit, and the alternatives in different browsers. This will need some familiarisation over time. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 20: June 24, 2020

**Today's Progress**: Expanding form.

**Thoughts:** (1) Adding buttons to survey form. At the moment, a good mechanism seems to be nesting a ```label``` element and a ```input``` element inside a ```div``` wrapper. (2) ```display: flex;``` should be used in the stead of ```display: -webkit-box;```, which is now outdated. (3) I'm learning how to modify the appearance and animations of radio buttons. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 21: June 25, 2020

**Today's Progress**: Learning about symbol usage in CSS.

**Thoughts:** (1) The ```+``` sign is an adjacent sigbling combinator. It applies to a secquence of elements within the same parent, and relies upn the fact that the second element (that following the ```+``` isgn) must come directly after the first element. The order is important! 
(2) In contrast, the ```~``` symbol is a general sibling combinator, and combines elements but does not need them to be called in any particular order within the parent element. 
(3) The ``` ``` (just a plain old space) sign, is often forgotten, but has a specific role too! It targets all children within it, even if they're nested within their own ```div``` elements (obviously, this can strongly depend on the style elements being defined). 
(4) The ```>``` sign is similar to the ``` ``` elements, but in contrast, it is only used to target the direct child elements of a specific parent. This means that in the following code, the second p element will not be affected, but all the others will!

```
div#container > p {
  color: red;
}
```
```
<div id="container">
    <p>First p element</p>
    <div>
        <p>Second p element</p> 
    </div> 
    <p>Third p element</p>
</div> 
```

### Day 22: June 26, 2020

**Today's Progress**: Reading about styling radio and checklist buttons. 

**Thoughts:** (1) Curious that radio buttons can't be styled. Instead, they must be removed, and replaced by a button designed by the user. So far, I have figured out how to remove them, and replace it with a new button. However, this button cannot yet be clicked, and I also need to create a new style when the button is clicked. I'm learning a lot of interesting methodology from this exercise. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 23: June 27, 2020

**Today's Progress**: Styling checklist buttons.

**Thoughts:** (1) Can't seem to prompt an animation from the unchecked state to the checked state. Will need to continue working on this tomorow. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 24: June 28, 2020

**Today's Progress**: Found bug.

**Thoughts:** (1) The checkbox buttons were not 'checking' because I had nested the ```input``` element within a ```div``` element, not a ```label``` element. Problem now solved. (2) I need to double check that I am making my webpages  

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 25: June 29, 2020

**Today's Progress**: Added a couple of new sections to my form.

**Thoughts:** (1) Added new sections to my form. (2) Started making the page responsive to different screen resolutions. Encountered a bug in which input boxes are not resizing as expected. Looking for my mistake. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 26: June 30, 2020

**Today's Progress**: Responsive web design. 

**Thoughts:** (1) Resonsive web design going well, and have fixed the bug in question; nothing important to note, just a matter of tracking fdown the responsible lines of code and fixing them. (2) Tomorrow I will go through an applied accessibility checklist to make sure my code is up to industry standards.  

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 27: July 1, 2020

**Today's Progress**: Buttons and animation.

**Thoughts:** (1) Making buttons and animating them. LEarning to animate quickly is going to be uesful, and this has been good practice. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 28: July 2, 2020

**Today's Progress**: Tweaking form to make sure it's up to standards.

**Thoughts:** (1) Learnt to use the ```required``` atribute, to ensure that certain form fields are filled in. It only applies to ```input```, ```select``` and ```textarea``` elements though. I had trouble applying ```required``` to an ```option``` within a ```select```, but I realised this was becase I had not given a value to the first option. This first ```option``` was a placeholder, and thus I gave it ```value=""```. I need to find out how to apply the same requirements to checkboxes and radio-buttons. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 29: July 3, 2020

**Today's Progress**: Applied accessibility training and application to form.

**Thoughts:** (1) I can link an ```label``` to an ```input``` with ```for=""``` and ```id=""``` attributes respectively. I have not found an equivalent for a drop down menu (2) Question: can I nest an entire survey page in a ```form``` element, as I might do with a ```main``` element, or does each individual question-and-answer section need to be nested in an individual ```form``` element. I'm not sure it this makes a differnce to people who need screen readers. I need to read more on the subject. 

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 30: July 4, 2020

**Today's Progress**: Completed the survey form!

**Thoughts:** (1) Finished off the survey form! (2) I would like to learn how to make more intersiting buttons at some point soon. Loads of fun ideas already exist for study, and it would be a good way to practice high-quality front-end develoment. (3) I've started thinking about the product landing lage that I will make next. I've found a [good style that I would like to replicate](http://rhythm.bestlooker.pro/index-07.html).

**Link to work:** [Survey form](https://codepen.io/SamHuguet/pen/MWKpVXp)

### Day 31: July 5, 2020

**Today's Progress**: Started a product landing page. 

**Thoughts:** (1) It's good practicing the main structure of HTML5 documents. I suspect that he scaffold will change significantly depending on the type of webpage that I make. (2) Established a background picture to the webpage and figured out how to modify the darkness of said picture. (3) Added a few (unstyled) buttons. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 32: July 6, 2020

**Today's Progress**: Added buttons. 

**Thoughts:** (1) When positioning, I realised that my method of centering vertically and horizontally doesn't always suit all purposes. For instace, if the entire parent container vertically and horizontally centers stuff (using ```flex```), it doesn't leave much room for varied positioning. Instead, this works quite well within the child element: 
```
position: absolute;
top: 50%;
left: 50%; 
transform: translate(-50%, -50%);
```
**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 33: July 7, 2020

**Today's Progress**: Styled buttons and organised them in grid. 

**Thoughts:** (1) Had some good practice creating and positioning elements within grid. (2) I need to get better at importing and manipulating fonts. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 34: July 8, 2020

**Today's Progress**: Menu

**Thoughts:** (1) Added a menu. (2) It's good to think of ```display: flex;``` as a method for organising elements in 1D space, whereas ```display:grid``` is a method of organising elements into 2D space. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 35: July 9, 2020

**Today's Progress**: Styling.

**Thoughts:** (1) I've been reading about use of ```text-transform:uppercase;```. It's useful ,and contrary to my suspicion, apparently does not *normally* impact the way in which a screen reader reads text. I say '*normally*' because screen readers can interprit all caps text as an acronym on occasion, which would obviously be fustrating. (2) I've been styling my page. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 36: July 10, 2020

**Today's Progress**: Styling.

**Thoughts:** (1) In order to make an ```a``` element work as a dud link, you can use an empty ```href=""``` attribute. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 37: July 11, 2020

**Today's Progress**: Styling and reading about button animations.

**Thoughts:** (1) In the past, I've been animating changes in ```div``` and ```button``` elements using the ```:hover``` selector. This works well, and requires that the ```:hover```-ed class have an ```animation-name```, which can then be linked to a ```@keyframes```At-rule. I've realised that in order to animade a button fading away, as the mouse ceases to hover over it, I might then need to use the ```:not(:hover)``` selector. However, I don't know whether this will work, and thus instead, I've found that I can animate a button fade-in and a button fade-out by describing the class, adding ```transition: 500ms;```, then describing the changes which might occur when hovering over the button. An example lies below: 

```
.navigation-link { 
  background- color: red; 
  transition: 700ms; 
}
.navigation-link:hover {
  background-color: white; 
}
```

I suppose that the disadvantage of this approach lies in the the fact that ```@keyframes``` gives finer temporal control over the animation. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)
