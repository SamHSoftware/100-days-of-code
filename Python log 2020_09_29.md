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

[Link to otsu-segmentation package](https://github.com/SamHSoftware/Image-Analysis/tree/main/otsu-segmentation)

### Day 7: October 5, 2020

**Today's Progress**: Learning how to make PyPA specification packages. 

**Thoughts:**  
(1) It's good that a system such as this with such good documentation exists. 

### Day 8: October 6, 2020

**Today's Progress**: Edited functions. 

**Thoughts:**  
(1) Function now saves a segmented image, as well as giving the user the option to print a subplot with the original image, the segmented image, and the histogram of pixel vales. 

[Link to otsu-segmentation package](https://github.com/SamHSoftware/Image-Analysis/tree/main/otsu-segmentation)

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

**Today's Progress**: Learning how to develop unit tests for my functions. 

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

[Link to otsu-segmentation package](https://github.com/SamHSoftware/Image-Analysis/tree/main/otsu-segmentation)

### Day 12: October 10, 2020

**Today's Progress**: Learning about using Git to version control locally and on GitHub. 

### Day 13: October 11, 2020

**Today's Progress**: Committed and pushed work to GitHub using Git. 

**Thoughts:**  
(1) Good progress, but I need to learn the nuances of using Git. I'll have a read through the documentation tomorrow. (2) Need to learn how to make a ```.gitignore``` file and understand how they work. 

### Day 14: October 12, 2020

**Today's Progress**: Learning how to use Git Bash.

**Thoughts:**  
(1) Had a problem with my gitignore. Turns out that after creating it as a text file, it needs to be renamed from .gitignore.txt to .gitignore, otherwise it won't work. 

### Day 15: October 13, 2020

**Today's Progress**: Learning how to use Git Bash.

**Today's Progress**: I think I've reached a point where I can quickly and safely version control my work with Git and GitHub. Time well spent I think. 

### Day 16: October 14, 2020

**Today's Progress**: Started creating a package to compare image filters.

[Link to comparing-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-filters)

### Day 17: October 15, 2020

**Today's Progress**: Continued work on package. 

**Thoughts:**  
(1) I think I'm going to create another package soon which focses on edge detection. There's a lot out there, and I'd quite like to practice.  
(2) Finished functions.  
(3) Need to make testing module next.  

[Link to comparing-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-filters)

### Day 18: October 16, 2020

**Today's Progress**: Finished the module file for my pckage to compare filters. 

[Link to comparing-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-filters)

### Day 19: October 17, 2020

**Today's Progress**: Wrote a unit testing file for my package. 

**Thoughts:**  
(1) Should the unit testing functions be called in a RUNME.py file? I'm not sure what the professional standard is. I will find out and make edits if necessary. 

[Link to comparing-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-filters)

### Day 20: October 18, 2020

**Today's Progress**: Wrote README.md file.

[Link to comparing-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-filters)

### Day 21: October 19, 2020

**Today's Progress**: Started writing module for edge detection. 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 22: October 20, 2020

**Today's Progress**: Added filters for edge detection module. 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 22: October 21, 2020

**Today's Progress**: Continued adding filters for edge detection module.  

**Thoughts:**  
(1) It would be fun and probably quite educational to make a module which takes the output of canny edge detection and colours the edges according to their gradient. 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 23: October 22, 2020

**Today's Progress**: Finished module. Added plotting capabilities.

**Thoughts:**  
(1) Came across a situation in which I needed to remove my last commit before pushing it up. I used the following code: 
```
git reset --soft HEAD~1
```

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 24: October 23, 2020

**Today's Progress**: Creating unit testing .py file for edge detection package. 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 25: October 24, 2020

**Today's Progress**: Worked on unit testing .py file for edge detection package. 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 26: October 25, 2020

**Today's Progress**: Worked on unit testing .py file for edge detection package. 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 27: October 26, 2020

**Today's Progress**: Worked on unit testing .py file for edge detection package. 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 28: October 27, 2020

**Today's Progress**: Submitted edge detection package. 

**Thoughts:**  
(1) I need to understand more of the mathematical basics behind machine learning. Time to educate myself! 

[Link to comparing-edge-detection-filters package](https://github.com/SamHSoftware/Image-Analysis/tree/main/comparing-edge-detection-filters)

### Day 29: October 28, 2020

**Today's Progress**: Learning mathematical basis behind machine learning.

**Thoughts:**  
(1) This is actually really useful, not just for ML, but also for my mathematical abilities as a whole. I haven't practiced calculus in ages! 

### Day 30: October 29, 2020

**Today's Progress**: Learning mathematical basis behind machine learning.

**Thoughts:**  
(1) Stuck on calculus. 

### Day 31: October 30, 2020

**Today's Progress**: Learning mathematical basis behind machine learning.

**Thoughts:**  
(1) OK, I've spent some time learning the calculus basics. I now understand the chain rule and the power rule, and I think that's going to get me a long way. 

### Day 32: October 31, 2020

**Today's Progress**: Learning mathematical basis behind machine learning.

**Thoughts:**  
(1) I think I now understand linear regression and cost functions, seperately and when combined to calculate coefficients of linear equations. 

### Day 33: November 1, 2020

**Today's Progress**: Worked on new machine learning package, to which I am committing a linear regression and gradient descent module. 

[Link to linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/linear-regression)

### Day 34: November 2, 2020

**Today's Progress**: Continuted work on linear-regression package. 

[Link to linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/linear-regression)

### Day 35: November 3, 2020

**Today's Progress**: Started working on unit testing. 

[Link to linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/linear-regression)

### Day 36: November 4, 2020

**Today's Progress**: Finished unit testing nad wrote README.md document for package. 

**Thoughts:**  
(1) I learnt how to use unit testing modules from within their own directory, as opposed to that which houses the RUNME.py files. Very useful.

[Link to linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/linear-regression)

### Day 37: November 5, 2020

**Today's Progress**: Learning about linear algebra prior to making a new ML package. 

### Day 38: November 6, 2020

**Today's Progress**: Learning more linear algebra. Started putting together multivariate linear regression package. 

**Thoughts:**  
(1) I learnt about identity matrices, alongside matric inversion and transposition. 

### Day 39: November 7, 2020

**Today's Progress**: Started work on multivariate linear regression package. 

**Thoughts:**  
(1) Included some basis functions for file selection and data import. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 40: November 8, 2020

**Today's Progress**: Starting to look at model construction with PyTorch. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 41: November 9 2020

**Today's Progress**: Continued work on multivariate linear regression package. 

**Thoughts:**  
(1) I think this package is going to take me a while. Each individual step isnt too tricky, but there's a fair bit to pick up. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 42: November 10, 2020

**Today's Progress**: Continued work on multivariate linear regression package. 

**Thoughts:**  
(1) Splitting data into testing and training sets. 
(2) I needed to preprocess my data and include a normalisation step. Model functions very well now. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 43: November 11, 2020

**Today's Progress**: Continued work on multivariate linear regression package. 

**Thoughts:**  
(1) Producting graphical methods of testing model performance. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 44: November 12, 2020

**Today's Progress**: Continued work on multivariate linear regression package. 

**Thoughts:**  
(1) Extracting the biases and weigths from model, as well as reading about how to assess model performance from a quantitative point of view. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 45: November 13, 2020

**Today's Progress**: Worked on unit testing for multivariate linear regression package. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 46: November 14, 2020

**Today's Progress**: Wrote the README.md document and finished off package. 

[Link to multivaritate-linear-regression package](https://github.com/SamHSoftware/Machine-Learning/tree/main/multivariate-linear-regression)

### Day 47: November 15, 2020

**Today's Progress**: Started working on a logistic classification package. 

**Thoughts:**  
(1) I'll need to do a bit of reading before relaly diving into this. 

[Link to logistic-classification package](https://github.com/SamHSoftware/Machine-Learning/tree/main/logistic-classification)

### Day 48: November 16, 2020

**Today's Progress**: Learning about logistic cost functions. 

### Day 49: November 17, 2020

**Today's Progress**: Continued working on a logistic classification package. 

[Link to logistic-classification package](https://github.com/SamHSoftware/Machine-Learning/tree/main/logistic-classification)

### Day 50: November 18, 2020

**Today's Progress**: Finished pakcage module with most of the functions. 

[Link to logistic-classification package](https://github.com/SamHSoftware/Machine-Learning/tree/main/logistic-classification)

### Day 51: November 19, 2020

**Today's Progress**: Began learning about neural networks so that I can begin coding one in Pytorch/Tensorflow. 

### Day 52: November 20, 2020

**Today's Progress**: Continued learning about neural networks and their implimentations. 

**Thoughts:**  
(1) I'm looking at some model representations, both from a conceptual point of view and from the point of view of linear algebra. Very useful, I think it'll take me a couple of days to build a mental picture of a network's functionality. 

### Day 53: November 21, 2020

**Today's Progress**: Continued learning about neural networks and their implimentations. 

**Thoughts:**  
(1) I''ve come across the concept of boolean functions. I've always understood concepts such as 'Or' and 'x And Not y', but I've never seen them represented in the form of 4 digit binary sequences. Curious to see where this leads. 

### Day 53: November 22, 2020

**Today's Progress**: Taking a pause from machine learning to code a package which converts simulation data to a usuable format. 

**Thoughts:**  
(1) Coding main module functions. 

[Link to simulations-to-xlsx package](https://github.com/SamHSoftware/PhD/tree/main/simulations-to-xlsx

### Day 54: November 23, 2020

**Today's Progress**: Leanring how to iteratively grow pandas dataframes. 

**Thoughts:**  
(1) This was useful. A slightly different approach to MATLAB's, i.e. build lists and append them to the df (python) rather that directly filling cells of a cell array (MATLAB). 

[Link to simulations-to-xlsx package](https://github.com/SamHSoftware/PhD/tree/main/simulations-to-xlsx)

### Day 55: November 24, 2020

**Today's Progress**: Debugging.

**Thoughts:**  
(1) I think I just came across floating point errors. I should read more about this to avoid issues in the future.  

[Link to simulations-to-xlsx package](https://github.com/SamHSoftware/PhD/tree/main/simulations-to-xlsx)

### Day 56: November 25, 2020

**Today's Progress**: Wrote unit testing module and finished package.

[Link to simulations-to-xlsx package](https://github.com/SamHSoftware/PhD/tree/main/simulations-to-xlsx)

### Day 57: November 26, 2020

**Today's Progress**: Back to learning about neural networks.

### Day 58: November 27, 2020

**Today's Progress**: Leanring about the use of neural networks for multiclass classification. 

### Day 59: November 28, 2020

**Today's Progress**: Putting neural netowrk learning into practice. Started designing network to classify breast tissue as benign or malignant. 

**Thoughts:**  
(1) Made initial commits and began designing network. It's going much faster with the practice I've had, and the architecture isn't too different from the logistic regression model that I made.  

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 60: November 29, 2020

**Today's Progress**: Continued work on neural network. 

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 61: November 30, 2020

**Today's Progress**: Adding graphical outputs to network function.

**Thoughts:**  
(1) Really useful. I've been reading about how to best represent model accuracy etc., and it looks like a confusion matrix is a good way to go. I've implimented one by adapting a preexisting function that I found. 

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 62: December 1, 2020

**Today's Progress**: Adding graphical outputs to network function.

**Thoughts:**  
(1) I've added an additional output in the form of a graph, displaying the validation loss and training loss per epoch. 

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 63: December 2, 2020

**Today's Progress**: Adding graphical outputs to network function.

**Thoughts:**  
(1) I've added an additional graph of validation and training accuracy, which I haven't done before, but has definitely been useful. 

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 64: December 3, 2020

**Today's Progress**: Started work on unit testing file. 

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 65: December 4, 2020

**Today's Progress**: Continued work on unit testing. 

**Thoughts:**  
(1) I've been implimenting a way of unit testing according to the final value of accuracy, and a fixed training set, but even so, I don't think this is ideal. Random weight initialisation means that there's always a bit of variation in the model outcome, which makes things hard to rigorously unit test. The method I'm using seems to be broadly working, but I think I should read more about this. 

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 66: December 5, 2020

**Today's Progress**: Finished the neural netowrk. 

[Link to neural-netowrk-breast-cancer package](https://github.com/SamHSoftware/Machine-Learning/tree/main/neural-network-breast-cancer)

### Day 67: December 6, 2020

**Today's Progress**: Learning about list comprehnesion in Python. Really useful for efficient coding. 

### Day 69: December 7, 2020

**Today's Progress**: Learning about machine learning techniques. 

### Day 70: December 8, 2020

**Today's Progress**:  Continued learning about machine learning techniques. 

**Thoughts:**  
(1) In particular, I'm looking at LSTMs. I think I'm jumping ahead a little in my learning, but I need to use one for time series dependent classification, and an LSTM would appear to be the way forward. 

### Day 71: December 9, 2020

**Today's Progress**: Began working on LSTM package. 

**Thoughts:**  
(1) Gradual start. I've implimented a funcion to allow for folder selection. 

[Link to LSTM-wave-classifier package](https://github.com/SamHSoftware/PhD/tree/main/LSTM-wave-classifer)

### Day 72: December 10, 2020

**Today's Progress**: Continued working on LSTM package. 

**Thoughts:**  
(1) Making funciton to process .xlsx data such that it can be used as training data for the LSTM. 

[Link to LSTM-wave-classifier package](https://github.com/SamHSoftware/PhD/tree/main/LSTM-wave-classifer)

### Day 73: December 11, 2020

**Today's Progress**: Continued working on LSTM package. 

**Thoughts:**  
(1) As above, still working on data processing function. 
(2) My understanding of list comprehension has come in handy during file filtering processes. 

[Link to LSTM-wave-classifier package](https://github.com/SamHSoftware/PhD/tree/main/LSTM-wave-classifer)

pandas series vs dataframe. 
