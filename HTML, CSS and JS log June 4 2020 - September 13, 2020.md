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

**Thoughts:** (1) In the past, I've been animating changes in ```div``` and ```button``` elements using the ```:hover``` selector. This works well, and requires that the ```:hover```-ed class have an ```animation-name```, which can then be linked to a ```@keyframes```At-rule. I've realised that in order to animade a button fading away, as the mouse ceases to hover over it, I might then need to use the ```:not(:hover)``` selector. However, I don't know whether this will work (*I've now tested this: It works, but it's much more inefficient to write out the differnt keyframe animations. Still useful to kknow about though*), and thus instead, I've found that I can animate a button fade-in and a button fade-out by describing the class, adding ```transition: 500ms;```, then describing the changes which might occur when hovering over the button. An example lies below: 

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

### Day 38: July 12, 2020

**Today's Progress**: Reading about and trying to impliment SVG images.

**Thoughts:** (1) I can include an .SVG using an ```img``` element, but I don't know how to modify the SVG fill color using css. I can tell there's a way, but it doesnt seem to revolve aorund the use of ```img``` elements. Thus I'm looking for documentation / a tutorial on this, but can't seem to find one as of yet. (2) I've found [this documentation](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web) which gives a good introduction to the topic. I think I will read about it today, then impliment it tomorrow. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 39: July 13, 2020

**Today's Progress**: More reading about and trying to impliment SVG images.

**Thoughts:** (1) Use of the ```svg``` tag isn't as simple as I thought it might be. There's a lot of new language which I havent come across before. I've found ways of resolving my problem with ```img``` tags, but I would prefer to be able to use this method too. The reading continues. (2) I've managed to include the SVG with the ```path``` tag, but I'm having trouble with the syling. The bottom was cut off, and while I solved this with ```overflow: visible;```, this wasn't exactly ideal. I've had a fiddle, and I think there are some styling conditions for ```svg``` elements which I'm not yet fully aware off. The reading continues, again! 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 39: July 14, 2020

**Today's Progress**: More reading about SVG images.

**Thoughts:** (1) Read abut the ```viewBox``` attribute to ```svg``` elements. It's a bit pernickety. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 40: July 15, 2020

**Today's Progress**: Use of viewbox and reading about SVG usage.

**Thoughts:** (1) I've been using the ```viewBox``` attribute and it's not an easy or efficient way to automate this process. I think I'm going to revert back to using an SVG within an ```img``` element. This has been good practice should I ever have to use ```svg``` elements and edit them using css. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 41: July 16, 2020

**Today's Progress**: Added a few new buttons and made page responsive to media queries.

**Thoughts:** (1) I'm wondering whether there's a way to make a page responsive to media queries, such that a block of html will simply *not appear* given a certain ```@media screen and (max-width: XYZ)``` rule. This is a little different to the modification of a css class or id given a partuclar rule. The latter I can do without problem. I can make the elements in question dissapear by simply moving off the page, but that seems to circumvent the problem somewhat. 

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)
    
### Day 42: July 17, 2020

**Today's Progress**: Submitted product landing page.

**Link to work:** [Product landing page](https://codepen.io/SamHuguet/pen/KKVQeKL)

### Day 43: July 18, 2020

**Today's Progress**: Started technical documentation page.

**Thoughts:** (1) Came across ```position:fixed;```, very useful. 

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 44: July 19, 2020

**Today's Progress**: Started making main styles for page.

**Thoughts:** (1) I'm getting much faster. Most of the main styling is done, with a navigation area and an area for the pages main content. (2) Came across this really clever way of [applying shadows to different sides of boxes.](http://jsfiddle.net/jDyQt/103).

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 45: July 20, 2020

**Today's Progress**: Styling and reading. 

**Thoughts:** (1) Came across an interesting issue, whereby the box-shadow of an element overlaps with adjacent elements. I would prefer the shadow to move underneath the adjacent element. To do this, one can seperate the shadow from it's parent element, by placing the box-shadow in a pseudoelement, using something like: 

```
.shadow { 
    position: relative; 
}
.shadow:after { 
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: -1;
  -webkit-box-shadow: 0 10px 20px rgba(0, 0, 0, 0.19),
      0 6px 20px rgba(0, 0, 0, 0.9);
}
```

(2) Also, I've come across ```z-index```, which is really useful. 

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 46: July 21, 2020

**Today's Progress**: Styling. 

**Thoughts:** (1) I've been messing aorund with bullet points, trying to style them, and I've noticed that when replacing old bullet points for new self-styled ones, ``` list-style-position: outside;``` no longer works. I'll do a little reading around to see what I can do to fix this. 

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 47: July 22, 2020

**Today's Progress**: Adding numerous sections.

**Thoughts:** (1) I'm using material from Free Code Camp to fill my technical documentation page. I will reference them at the end. (2) Learnt to use ```&lt;``` to print '<' as text, and ```&gt;``` to print '>' as text. (3) When including white space, to simulate a tab, I can insert the following: 

```
<span style="display:inline-block; width: 10px;"></span>
```

(4) I came across the ```code``` element. Very useful. 

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 48: July 23, 2020

**Today's Progress**: Adding numerous sections.

**Thoughts:** (1) Continued adding sections to my page. (2) Fixed an issue I was having with ```overflow: none```, which proved to be very useful. 

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 49: July 24, 2020

**Today's Progress**: Added final sections. 

**Thoughts:** (1) Added last few sections and a final list of references. 

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 50: July 25, 2020

**Today's Progress**: Make page responsive to media queries. Submitted project.

**Thoughts:** (1) Made page responsive to media queries, and came across ```overflow-y``` and ```overflow-x```, which was useful. (2) I need to read more about z-index. It's not as simple as I first anticipated. (3) Submitted work! 

**Link to work:** [Technical Documentation Page](https://codepen.io/SamHuguet/pen/bGEQQbg?editors=1100)

### Day 51: July 26, 2020

**Today's Progress**: Started personal portfolio page.

**Thoughts:** (1) Came across the ```meta``` tag. It provides a lot of useful info to go in ```head``` elements. I'll be using ```meta``` elements from now on. 

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 52: July 27, 2020

**Today's Progress**: Practicing with image sizing again.

**Thoughts:** (1) The ```background-image``` property is good, but I want to see if I can achieve the same using a normal ```img``` tag. So far, no such luck. 

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 53: July 28, 2020

**Today's Progress**: Made a reusualble scaffold structure. 

**Thoughts:** (1) Made the following for re-use in differnt pages:
```
<!DOCTYPE HTML>

<html> 
 
  <head> <!-- meta info --> 
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="keywords" content="keyword1, keyword2, keyword3, etc.">
    <meta name="description" content="A description of the page">
    <meta name="author" content="Sam Huguet">
    <meta http-equiv="refresh" content="30">
  </head> 
 
  <body> 
    <nav></nav> 
    <main></main> 
    <footer></footer> 
  </body> 
  
</html>
```

```
html { 
    scroll-behavior: smooth;
    }
```
### Day 54: July 29, 2020

**Today's Progress**: Restarted page. 

**Thoughts:** (1) I didn't like the way the page was going, so I started again. (2) When adding a background to the ```body```, I can use the following: 

```
background: -webkit-gradient(linear, right top, left bottom, from(#01615c), to(#0ca857)) fixed;
```

(2) I need to start learning JS soon. I keep coming across instances for which it would be useful. 

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 55: July 30, 2020

**Today's Progress**: Vertical text.

**Thoughts:** (1) Vertical text doesn't appear to have a one-size-fits-all solution. I'm trying to figure out what the industry gold standard is so that I can impliment something robust. 

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 56: July 31, 2020

**Today's Progress**: Added page structure.

**Thoughts:** (1) Practicing with flexbox and grids. (2) Should I be compiling code snippets which perform functions across multiple browsers? 

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 57: August 1, 2020

**Today's Progress**: Added page structure.

**Thoughts:** (1) Had issues organsing a grid. Need to do some reading. 

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 58: August 2, 2020

**Today's Progress**: Learning more about fractional units. 

**Thoughts:** (1) Came across an issue in which I used ```grid-template-columns: repeat(2, 1fr)``` to create a couple of columns. However, when differnt content was added to each grid-item, they were of varying widths. I wanted them to be of equal dimensions. Now, I learnt some important lessons: ```1fr``` is actually shorthand for ```minmax(auto, 1fr)```. The '```auto```' was the issue, as it pushed the minimum size of the grid-items to the largest minimum size possible of the grid items occupying the grid track. Thus, the problem was solved by replacing the line of code with ```grid-template-columns: repeat(3, minmax(0, 1fr));```. (2) I need to read and learn about AJAX.

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 59: August 3, 2020

**Today's Progress**: ertical text breakthrough.

**Thoughts:** (1) for vertical text which can be horizontally and verticlaly center-aligned, use the following: 

```
.parent { 
  display: flex; 
  justify-content: center;
  align-items: center; 
}

.child { 
  writing-mode: vertical-rl;
  transform: rotate(180deg);
}
```
(2) Included a fair number of media queries. I've realised that I've been making media queries responsive to changes to the width of the page, not to it's height. I'll need to correct this. 

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 60: August 4, 2020

**Today's Progress**: Aspect ratio reading and implimentation. 

**Thoughts:** (1) I needed a ```div``` to have a height of 100%, and a width equal to it's responsive height. An intersting mechanism for doing this came in the following form: 

```
.container {
  width: 100%;
  padding-top: 100%; /* 1:1 Aspect Ratio */
}
```

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 61: August 5, 2020

**Today's Progress**: Made page responsive to media queries and submitted project.

**Thoughts:** (1) JavaScript is next!!

**Link to work:** [Personal Portfolio Page](https://codepen.io/SamHuguet/pen/BajEdXm?editors=1100)

### Day 62-100: August 6 - September 13, 2020

**Today's Progress**: Learning JS basics. 

**Thoughts:** 
(1) It's interesting learning about the different data types and how they correlate with those of other languages I've learnt.  
(2) I'm looking forward to using this in concert with HTML and CSS.  
(3) Is JS compatable to the same degree with every browser? It'd be useful to find out.   
(4) [This](https://stackoverflow.com/questions/2802055/what-does-the-construct-x-x-y-mean/2802064) thread has blown my mind. The double pipe operator is way more complex than I initially imagined.    
(5) I've been reading about ternary operators, really fluid coding.    
(6) Intersting differences between ```var```, ```let``` and ```const```. Also, I've been reading about the concept of hoisting. Very interesting.   
(7) Learnt about regular expressions.   
(8) I have learnt about JS as a pass by reference language. I have consolidated these thoughts into a lesson:   

Definition of a 'pass by reference' (PBR) language: 
- If you mutate a varibale within a function, the mutation **will be** inflected back to the variable outside the function. 

Definition of a 'pass by value' (PBV) language: 
- If you mutate a variable within a function, the mutation will **not** be inflected back to the variable outside the function. 

Here is **EXAMPLE 1: Primitive value reassignment**: 
```
let a = 1; 

let change = (val) -> { 
   val = 2;
};

change(a); 
console.log(a); \\ 1
```
The output, ```1```, gives the impression that it's a case of PBV... but this is not the case!  

JS always uses PBR... some people say that primitive values (data like the number 1) use PBV, whereas objects use PBR. Again, this is wrong. **JS always uses PBR**.  

Why? Hang in there. We need another couple of examples first. 

Here is **EXAMPLE 2: Object reassignment**: 
```
let a = {num:1}; 

let change = (val) -> { 
   val = {};
};

change(a); 
console.log(a); \\ {num:1}
```

Again... it looks like PBV, right? Surely if JS if PBR, the variable ```a``` should have changed to an empty object, like ```{}```.  

This is not the case. The next exampe proves that JS is PBR. 

Here is **EXAMPLE 3: Object mutation**: 
```
let a = {num:1}; 

let change = (val) -> { 
   val.num = 2;
};

change(a); 
console.log(a); \\ {num:2}
```  
As we can see, this example demonstrates PBR, as the variable ```a``` (found within a scope outside of the function) **is** changed (from within the scope of the function).  

But why didn't a change reflect in example 2?  

Becuase, we weren't **mutating** the object, we were completely **reassigning** it to an empty object. This is key. Within the function, for PBR to work, the ```=``` operator needs to be able to **mutate** the object in question. When it is forced to **reassign** the object, as in example 2, then the reference to that 'computer address' breaks, and a completely new varibale is made within the function. In this case, ```val``` was reassigned to store ```{}```.  

Ok, but what about example 1. That still looks like PBV, right? Nope, still PBR. 

In example 1, JS does indeed pass a reference of the primitive value (the number 1) into the function. However, JS cannot mutate primitive numbers, it can only ever reassign them when the ```=``` is used. Therefore, JS has to reassign the value of ```a```. As with the last example, when reassignment is used, the 'reference' to the variable address cannot be kept. As a result, a new, unrelated variable (```val```) is made (reassigned) within the scope of the function.  

So during reassignment, it looks like we loose the reference, the address to the data of the variable in question.  

Here is a **Final EXAMPLE:**
```
let a = {num:1};
let b = a;

console.log(a); \\ {num:1} 
console.log(b}; \\ {num:1} 
```
Unsuprisingly, ```b``` adopts the identity of ```a```. 
Upon mutation of ```a```... 
```
a.num = 2; 
console.log(a); \\ {num:2} 
console.log(b}; \\ {num:2} 
```
... ```b``` adopts the value of ```a```, as JS works via PBR, and we've just done a mutation, which allows for PBR. 
But here, we now reassign ```a```...
```
a.num = {}; 
console.log(a); \\ {} 
console.log(b}; \\ {num:2} 
```
... The value of ```a``` changes, as it has been reassigned to an empty object. ```b``` stays exactly the same though! Reassignment has been used, and so it's link to ```a``` is lost. 

### Overall Thoughts. 

This has been a great challange. The best way for me to stay motivated was to log items in discrete chunks. Thus the project work for HTML and CSS was easy to do! The JS was harder, not necessarily becuse of the content, but because I was learning smaller packages of information. As a result, my learning was more of a continuous change over time, and thus was harder to log into discrete sections. I think that next time, I'll try to improve my logging when learning. This will probably improve my determination to keep going, especially while writing my PhD thesis. 
