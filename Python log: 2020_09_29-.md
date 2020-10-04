# 100 Days Of Code - Log

### Day 1: September 29, 2020

**Today's Progress**: Learning Python basics. 

**Thoughts:** Useful practice, and mostly basic with many simlarities to other languages. 

### Day 2: September 30, 2020

**Today's Progress**: Started making python functions.

**Thoughts:** Did some useful practice exercises. 

### Day 3: October 1, 2020

**Today's Progress**: Learnt how to use Anaconda. Also started making a resositry of functions. 

**Thoughts:**  
(1) Made a fucntion which, when called, uses Tkinter to open a file-selection dialog box.  
(2) I need to practice more with tkinter over time and read on it. I think it'll be pretty helpful in the future. 

### Day 4: October 2, 2020

**Today's Progress**: Making image analysis functions. 

**Thoughts:**  
(1) Made a fucntion which, when called, uses applies a median filter to an image.  
(2) Made a function which, when called, plots the pixel intensity distribution of the image in question.  

### Day 5: October 3, 2020

**Today's Progress**: Making image analysis functions. 

**Thoughts:**  
(1) Used the following code to be ensure that upon highlighting code within JupiterLab, and upon pressing ```F9```, the selected code will run in the console.  
```
{
    // List of Keyboard Shortcuts
    "shortcuts": [
        {
            "command": "notebook:run-in-console",
            "keys": [
                "F9"
            ],
            "selector": ".jp-Notebook.jp-mod-editMode"
        },
    ]
}
```
(2) Got most of the way through making a function to segment an image using a threshold determined by the Otsu algorithm. Unfortnately, it's almost behaving like Otsu has provided a multi-level threshold... I've found a function which works though, so I'll use it to reverse engineer the correct way to threshold tomorrow. 

### Day 6: October 4, 2020

**Today's Progress**: Making Otsu thresholding function

**Thoughts:**  
(1) Made Otsu thresholding function. The bug from yesterday was caused by the import of an image using matplotlib as opposed to cv2. 
(2) Need to iron out a graphing bug within which the histogram is placed ontop of my segmentation output. SOLUTION: Include ```plt.show()``` after each `plt.imshow(image)```.
