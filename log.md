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

**Thoughts:** (1) I've learnt about using a ```<link>``` tag link to an external style sheet. This is particularly useful when considering. (2) Vertical align a child element by adding to following to it's parent:   

    ```display: flex;```  /*Make the container a flex container*/ 
    
    ```align-items: center;``` /*Vertical alignment*/ 
    
    ```justify-content: center;``` /*Horizontal alignment*/ 

**Link to work:** [Tribute page](https://github.com/SamHSoftware/HTML-and-HTML5/tree/master/Tribute%20page:%20William%20Earnest%20Henley)
