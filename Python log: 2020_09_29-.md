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
(2) Need to iron out a graphing bug within which the histogram is placed ontop of my segmentation output. SOLUTION: Include ```plt.show()``` after each ```plt.imshow(image)```.

### Day 7: October 5, 2020

**Today's Progress**: Learning how to make PyPA specification packages. 

**Thoughts:**  
(1) It's good that a system such as this with such good documentation exists. 

### Day 8: October 6, 2020

**Today's Progress**: Edited functions. 

**Thoughts:**  
(1) Function now saves a segmented image, as well as giving the user the option to print a subplot with the original image, the segmented image, and the histogram of pixel vales. 

### Day 9: October 7, 2020

**Today's Progress**: Learning how to make requirements.txt files. 

**Thoughts:**  
(1) I've been learning about the best practices for python package distribution. PIP requirements.txt files are a vital part of this process. They can be made with the following code, run within the Anaconda Promt (Anaconda3).

```
conda activate <env>
conda install pip
pip freeze > requirements.txt
```
For example, if I wanted to make a requirements file for the 'HelloWorld' environment, I would use the following code: 

```
conda activate HelloWorld
conda install pip
pip freeze > requirements.txt
```
If, however, I want to make a conda specific requirements file, I can use the following: 
```
conda activate <env> 
conda list -e > requirements.txt
```

### Day 10: October 8, 2020

**Today's Progress**: LEarning how to develop unit tests for my functions. 

**Thoughts:**  
#### Uses of unit testing:
- Tests reduce bugs following the addition of new features and in existing features. 
- Unit tests use the functions in question, and thus, good unit tests are good documentation!
- Tests reduce cost of changing code. 
- They make for faster debugging and development.
- Unit testing allows for better disign of our project in the first place.  

#### What resources are available for unit testing in Python? 
(1) ```unittest``` - In the Python standard library.  
(2) ```nose``` - Not instandard library, but is more simple than ```unittest```.  
(3) ```pytest``` - Not in standard library.  

#### General notes: 
(1) Add ```test_``` as a prefix to your unit testing file. 

### Day 11: October 9, 2020

**Today's Progress**: Made test files and completed my package for Github. 
